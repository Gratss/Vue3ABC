<script>
export default{
data(){
return{
    SUPRA: ['Toyota','Supra','A800']
}
},
methods: {
add: function(){
this.Supra.push('Moya');
},
del: function(){
this.Supra.shift();
},
del1: function () {
this.Supra.pop();
},
splice: function(){
this.Supra.splice(2, 1);
},
sort: function(){
this.Supra.sort();
},
reverse: function () {
    this.Supra.reverse();
},
}
}
</script>
Glebchikkk
<template>
<ul>
<li v-for="elem in Supra">{{ elem }}</li>
</ul>
<button @click="add">1</button>
<br>
<button @click="del">2</button>
<br>
<button @click="del1">3</button>
<br>
<button @click="splice">4</button>
<br>
<button @click="sort">5</button>
<br>
<button @click="reverse">6</button>
</template>

<style >
</style>