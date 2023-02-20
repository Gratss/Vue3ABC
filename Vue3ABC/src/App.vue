<script>
export default{
data(){
return{
    cssClasses: 'Supra',
}
}
}
</script>
Glebchikkk

<template>
<p :class="cssClasses">Supra</p>
</template>

<style >
.Supra {
    padding: 10px;
    margin: 10px;
    background: rgb(160, 204, 0);
    color: rgb(255, 255, 255);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
</style>