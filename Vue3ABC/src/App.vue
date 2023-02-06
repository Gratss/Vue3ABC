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
<a class="inline-link-1" href="https://ru.wikipedia.org/wiki/Toyota_Supra" onclick="event.preventDefault()">Supra</a>
<br>
<br>
<button @click.once="show">Supra</button>
</template>

<style >
</style>