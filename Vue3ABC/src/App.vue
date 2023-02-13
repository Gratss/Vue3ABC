<script>
export default{
data(){
return{
    SUPRA: {a:'100$', b:'200$', c:'300$'},
}
}
}
</script>
Glebchikkk
<template>
<ul>
    <li v-for="elem in SUPRA">{{ elem }}</li>
</ul>
<br>
<br>
<ul>
    <li v-for="(key, elem) in SUPRA"> {{ elem }} - {{ key }}</li>
</ul>
<br>
<br>
<ul>
    <li v-for="(key, elem, index) in SUPRA"> {{ elem }} - {{ key }} - {{ index }}</li>
</ul>
<br>
<br>
<ul>
    <li v-for="(key, elem, index) in SUPRA"> {{ elem }} - {{ key }} - {{ index+1 }}</li>
</ul>
</template>

<style >
</style>