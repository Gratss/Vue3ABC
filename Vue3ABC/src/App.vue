<script>
export default{
data(){
return{
    SUPRA: [1, 2, 3, 4, 5],
}
}
}
</script>
Glebchikkk
<template>
<div v-for="elem in supra">{{ elem }}</div>
<br>
<div v-for="elem in supra">{{ elem*elem }}</div>
<br>
<ul v-for="elem in supra">{{ elem }}</ul>
</template>

<style >
</style>