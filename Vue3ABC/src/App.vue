<script>
export default{
data(){
return{
    visible: true,
btnHide: true,
btnVis: false,
}
},
methods: {
hide: function(){
    this.visible = false;
    this.btnHide = false;
    this.btnVis = true;
},
vis: function(){
    this.visible = true;
    this.btnHide = true;
    this.btnVis = false;
}
}
}
</script>
Glebchikkk
<template>
<button @click="vis" v-if="btnVis">visible</button>
<button @click="hide" v-if="btnHide">hide</button>
<p v-if="visible">SUPRA</p>
</template>

<style >
</style>