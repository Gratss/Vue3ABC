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
    edit(student) {
    student.isEdit = true;
},
save(student) {
    student.isEdit = false;
},
}
}
</script>
Glebchikkk

<template>
<table>
<tr v-for="student in students" :key="student.id"> 
<template v-if="!student.isEdit">
{{ student.name }} {{ student.surn }} {{ student.salary }} {{ student.age }}<button class="button" @click="edit(student)">Изменить</button>
</template>
<template v-else>
<input v-model="student.name">
<input v-model="student.surn">
<input v-model="student.salary">
<input v-model="student.age"><button class="button" @click="save(student)">Сохранить</button>
</template>
</tr>
</table>
</template>

<style scoped>
</style>