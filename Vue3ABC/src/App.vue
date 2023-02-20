<script>
export default{
data(){
return{
message: 'Gleb',
number: '+7978233355599',
}
},
methods: {
}
}
</script>
Glebchikkk

<template>
<input class="text-field__input" v-model="message">
<p :style="{textTransform: 'uppercase'}">{{ message }}</p>
<br>
<input class="text-field__input" v-model="number">
<p>{{ number*number }}</p>
</template>

<style>
</style>