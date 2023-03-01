<script>
import Supra from './components/User.vue'


export default {
data() {
    return {
    Supra: [
        {
        id: 1,
        name: 'Toyota',
        surn: 'Supra'
        },
        {
        id: 2,
        name: 'Supra',
        surn: 'Supra'
        },
        {
        id: 3,
        name: 'A80',
        surn: 'Supra'
        },
    ],
    }
},
components: {
    Supra
},
methods: {
    remove(id) {
    this.Supra = this.Supra.filter((Supras) => {
        return Supras.id !== id;
    })
    }
}
}
</script>
Glebchikkk

<template>
<Supra v-for   ="Supras in Supra"
		:id     ="Supras.id"
		:name   ="supras.name"
		:surn   ="supras.surn"
		@remove ="remove"
		:key    ="supras.id"/>
</template>
<style>
</style>