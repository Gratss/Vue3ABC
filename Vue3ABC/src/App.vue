<script>
import Supra from './components/User.vue'


export default {
data() {
    return {
    Supra: [
        {
        id: 1,
        name: 'Toyota',
        surn: 'Supra'
        },
        {
        id: 2,
        name: 'Supra',
        surn: 'Supra'
        },
        {
        id: 3,
        name: 'A80',
        surn: 'Supra'
        },
    ],
    }
},
components: {
    Supra, UserForm
},
methods: {
    add(name, surn){
    let id = this.supra.length + 1;
    this.supra.push({
        id, name, surn
    });
    }
}
}
</script>

<template>
<UserForm @add="add"/>
</template>

<style>
</style>