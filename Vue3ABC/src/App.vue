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
    SupraName(name) {
    console.log(name);
    },
}
}

</script>
Glebchikkk

<template>
<Supra @show="supraName"/>
</template>
<style>
</style>