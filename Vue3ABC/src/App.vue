<script>
export default{
data(){
return{
    isSupra: [1, -2, 3, -4, 5],
}
}
}
</script>
Glebchikkk
<template>
<ul>
    <template v-for="elem in isSupra">
    <li v-if="elem > 0 ">{{ elem }}</li>
    </template>
</ul>
</template>

<style >
</style>