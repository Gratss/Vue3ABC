<script>
import Supra from './components/User.vue'
export default {
data() {
    return {
    Supra: [
        {
        id: 1,
        name: 'Gleb',
        salary: 95000,
        age: 18
        },
        {
        id: 2,
        name: 'Edem',
        salary: 90000,
        age: 18
        },
        {
        id: 3,
        name: 'Edem',
        salary: 90000,
        age: 18
        },
    ],
}
},
components: {
    Supra
}
}
</script>
Glebchikkk

<template>
<Supra v-for="supras in smeshariki" :name="supras.name" :salary="supras.salary" :age="supras.age" :key="supras.id" />
</template>
<style>
</style>