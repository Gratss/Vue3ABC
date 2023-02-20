<script>
export default{
data(){
return{
    num: 0,
    res: 0,
sum: 0,
num1: 0, 
num2: 0,
}
},
methods: {
Supra: function () {
    this.res = Math.sqrt(this.num);
},
supra:function(){
    this.sum = this.num1 + this.num2;
}
}
}
</script>
Glebchikkk

<template>
<p>{{ res }}</p>
<input class="text-field__input" v-model="num">
<button @click="supra">квадратный корень</button>
<br>
<p>{{ sum }}</p>
<input class="text-field__input" v-model=num1>
<input class="text-field__input" v-model=num2>
<button @click="supra">сумма</button>
<br>
</template>

<style>
</style>