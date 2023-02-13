<script>
export default{
data(){
return{
    supra: true,
}
},
methods: {
SUPRA: function(){
this.supra = false;
}
}
}
</script>
Glebchikkk
<template>
<button @click="supra">supra</button>
<p v-show="supra">A80</p>
</template>

<style >
</style>