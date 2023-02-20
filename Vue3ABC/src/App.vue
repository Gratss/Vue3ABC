<script>
export default{
data(){
return{
    isDisabled: true,
    isDisabled1: true,
    checked: false,
}
},
methods: {
Supra: function () {
    this.isDisabled = false;
},
Supra: function () {
    this.isDisabled1 = false;
},
}
}
</script>

<template>
<input type="text" class="text-field__input"  v-bind:disabled="isDisabled">
<br>
<button @click="Supra">Supra</button>
<br>
<br>
<br>
<input type="text" class="text-field__input" v-bind:disabled="isDisabled1">
<br>
<input type="checkbox" v-model="checked" @click="Supra">
<button @click="Supra">Supra</button> 
</template>

<style>
</style>