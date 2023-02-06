<script>
export default{
data(){
return{
    visible: true,
    visible2: true,
    visible3: true,
}
},
methods: {
Toyota: function(){
    this.visible = !this.visible;
},
Supra: function () {
    this.visible2 = !this.visible2;
},
A80: function () {
    this.visible3 = !this.visible3;
}
}
}
</script>
Glebchikkk
<template>
<button @click="Toyota">Toyota</button>
<p v-if="visible">Toyota</p>
<button @click="Supra">Supra</button>
<p v-if="visible2">Supra</p>
<button @click="A80">A80</button>
<p v-if="visible3">A80</p>
</template>

<style >
</style>