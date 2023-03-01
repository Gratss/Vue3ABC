<script>
export default{
data(){
return{
    students: [
    {
        id: 1,
        name: 'Gleb',
        surn: 'Selivanov',
        salary: 100,
				age: 18,
    },
    {
        id: 2,
        name: 'Edem',
        surn: 'Seytumerov',
        salary: 200,
				age: 18,
    },
    {
        id: 3,
        name: 'Edem',
        surn: 'Asanov',
        salary: 300,
				age: 18,
    },
    ],
}
},
methods: {
removeStudents: function (id) {
    this.students = this.students.filter((student) => {
    return student.id !== id;
    })
}
}
}
</script>
Glebchikkk

<template>
<table>
<tr v-for="student in students" :key="student.id"> {{ student.name }} {{ student.surn }} {{ student.salary }} {{ student.age }} <button class="button" @click="removeStudents(students.id)">remove</button>
</tr>
</table>
</template>

<style>
</style>