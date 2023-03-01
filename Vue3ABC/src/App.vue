<script>
import Supra from './components/User.vue'
export default {
data() {
    return {
    name: 'Gleb',
    salary: '95000',
    age: '18',
    }
},
components: {
    Supra
}
}
</script>
Glebchikkk

<template>
<Supra :name="name" :salary="salary" :age="age"/>
</template>
<style>
</style>