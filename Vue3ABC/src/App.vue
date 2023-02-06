<script>
export default{
data(){
},
methods: {
show: function(){
    alert(new Date().toLocaleDateString());
}
}
}
</script>
Glebchikkk
<template>
<button  v-on:mouseover="show">Наведение</button>
<button  @click="show">Нажатие</button>
</template>

<style >
</style>