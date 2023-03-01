<script>
import Supra from './components/User.vue'
export default {
data() {
    return {
    
    }
},
components: {
    Supra
},
methods: {
    aaa(name) {
    console.log(name);
    },
    bbb(name, salary){
console.log(name, salary);
    }
}
}
</script>
Glebchikkk

<template>
<Supra @show="aaa" @show1="bbb"/>
</template>
<style>
</style>