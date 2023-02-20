<script>
export default{
data(){
return{
    isValid: true,
    isDisabled: true,
}
}
}
</script>

<template>
<p :class="{SUPRA: isValid, disable: isDisabled}">supra</p>
</template>

<style >
p.supra{
padding: 10px;
margin: 10px;
background: rgb(245, 226, 15);
color: rgb(245, 22, 22);
font-weight: bold;
text-decoration: none;
}
</style>