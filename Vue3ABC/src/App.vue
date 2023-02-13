<script>
export default{
data(){
return{
    SUPRA: [1, 2, 3],
}
}
}
</script>
Glebchikkk
<template>
<div v-for="elem in SUPRA">
<p>{{ elem }}</p>
<p class="divider"> </p>
</div>
<br>
<ul v-for="elem in SUPRA">
    <li>{{ elem }}</li>
    <li class="divider"> </li>
</ul>
</template>

<style >
</style>