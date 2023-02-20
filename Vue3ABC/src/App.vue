<script>
export default{
data(){
return{
    cssClasses: 'Supra',
    visible: true,
    style: {
    hidden: true,
}
}
},
methods: {
setDone:function(){
this.style.hidden = false;
},
setTwo: function(){
this.style.hidden = true;
},
supra: function () {
    this.visible = !this.visible;
}
}
}
</script>
Glebchikkk

<template>
<button @click="supra">supra</button>
<p class="supra" v-if="visible">supra</p>
<p :class="style">Conclave</p>
<button @click="setDone">показывает</button>
<button @click="setTwo">прячет</button>
</template>

<style >
.Supra {
    padding: 10px;
    margin: 10px;
    background: rgb(160, 204, 0);
    color: rgb(255, 255, 255);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
p.hidden{
display: none;
}
</style>
