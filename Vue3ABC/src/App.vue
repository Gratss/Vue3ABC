<script>
export default{
data(){
return{
    text: 'A80',
}
},
methods: {
change: function(){
    this.text = 'Toyota';
},
change2: function(){
this.text = 'Supra'
}
}
}
</script>
Glebchikkk
<template>
<p>{{ text }}</p>
<button @click="change">Toyota</button>
<button @click="change2">Supra</button>
</template>

<style >
</style>