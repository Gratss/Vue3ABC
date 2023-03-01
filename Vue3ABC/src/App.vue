<script>
export default{
data(){
return{
    supra: '',
    supra: ['Toyota', 'Supra', 'A80'],
}
},
methods: {
addSmeshariki: function () {
    this.supra.unshift(this.supra);
}
}
}
</script>
Glebchikkk

<template>
    <ul>
    <li v-for="(item, index) in 
                Supra" :key="index">
        {{ item }}
        <br>
        <button @click="removeSupra(index)">Del</button>
    </li>
    </ul>
    </template>
    
    <style>
    </style>
    