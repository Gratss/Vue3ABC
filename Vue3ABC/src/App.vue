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
<p>Pin</p>
<p>Nyusha</p>
<p>Krosh</p>
</div>
</template>

<style >
</style>