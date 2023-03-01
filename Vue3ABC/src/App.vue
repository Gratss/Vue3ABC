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
    Supra() {
    alert('Toyota, Supra, A80');
    },
    Student(){
    alert('Gleb, Edem, Edem')
    }
}
}

</script>
Glebchikkk

<template>
<Supra @show="Supra" @show1="Student" />
</template>
<style>
</style>