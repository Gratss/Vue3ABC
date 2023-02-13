<script>
export default{
data(){
return{
    SUPRA: [
    {
        id: 1,
        name: 'Toyota',
    },
    {
        id: 2,
        name: 'Supra',
    },
    {
        id: 3,
        name: 'A80',
    },
    ]
}
}
}
</script>
Glebchikkk
<template>
<p class= "styled" v-for="prod in Supra" :key='Supra.id'>{{ prod.name }}</p>
</template>

<style >
</style>