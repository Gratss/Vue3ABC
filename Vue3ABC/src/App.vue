<script>
export default{
data(){
return{
    SUPRA: ['x', 'y', 'z'],
}
}
}
</script>
Glebchikkk
<template>
<ul v-for="(elem, key) in supra"> {{ key }} {{ elem }}</ul>
</template>

<style >
</style>