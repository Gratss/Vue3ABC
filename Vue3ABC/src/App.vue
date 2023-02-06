<script>
export default{
data(){
return{
    visible: true,
    visible1: false,
	hidden: true,
    hidden1: false,
}
},
}
</script>
Glebchikkk
<template>
<p v-if="visible">Toyota</p>
<p v-if="!visible1">Supra</p>
<p v-if="hidden">A80</p>
<p v-if="!hidden1">1994</p>
</template>

<style >
</style>