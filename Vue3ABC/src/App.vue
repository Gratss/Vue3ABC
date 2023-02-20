<script>
export default{
data(){
return{
    cssClasses: 'Supra',
    obj: {
    done: true,
    selected: false,
}
}
}
}
</script>
Glebchikkk

<template>
<p :class="cssClasses">Supra</p>
<p :class="obj">A80</p>
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
.selected{
    padding: 10px;
    margin: 10px;
    background: rgb(234, 129, 16);
    color: white;
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
.done {
    padding: 10px;
    margin: 10px;
    background: rgb(20, 247, 213);
    color: rgb(12, 51, 245);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
</style>