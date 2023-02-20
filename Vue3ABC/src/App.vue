<script>
export default{
data(){
return{
    check_mark: true,
    visible: true,
}
},
methods: {
Supra: function () {
    this.check_mark = false;
    this.visible = !this.visible;
},
}
}
</script>
Glebchikkk

<template>
<input class="text-field__input" type="checkbox" v-model="check_mark"> 
<button @click="Supra">Supra</button>
<p v-if="visible">{{ check_mark ? 'A80' : 'Toyota' }}</p>
</template>

<style>
</style>