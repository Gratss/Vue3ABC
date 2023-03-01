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
    <ul class="styled">
    <li v-for="(item, index) in 
                Supra" :key="index">
        {{ item }}
    </li>
    </ul>
    <input class="text-field__input" v-model="Supra">
    <br>
    <button @click="addSupra">add</button>
    </template>
    
    <style>
    </style>
    