<script>
export default{
data(){
return{
    num1: 1,
    num2: 2,
    text: 'polina'
}
},
methods: {
show: function(){
    let text = this.cape(this.text)
    alert(text);
    // сумма чисел;
},
cape: function(str){
    return str[0].toUpperCase() + str.slice(1);
}
}
}
</script>
Glebchikkk
<template>
<div>{{ text }}</div>
<div>{{ num1 + num2 }}</div>
<button v-on:mouseover="show">Наведение</button>
<button @click="show">Нажатие</button>
</template>

<style >
</style>