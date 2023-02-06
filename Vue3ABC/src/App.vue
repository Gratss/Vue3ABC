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

<template>
<button @click="show">data</button>
</template>

<style >
</style>