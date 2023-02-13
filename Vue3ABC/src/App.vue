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
Glebhcikkk
<template>
<button @click="supra">supra</button>
<div v-if="supra">
<p>Toyota</p>
<p>Supra</p>
<p>A80</p>
</div>
</template>

<style >
</style>