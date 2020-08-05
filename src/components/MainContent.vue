<template>
    <div>
        <Intro/>
        <History/>
        <Companies/>
        <Weapon/>
    </div>
</template>

<script>
import Intro from './content/Intro.vue'
import History from './content/History.vue'
import Companies from './content/Companies.vue'
import Weapon from './content/Weapon.vue'

export default {
    name: 'MainContent',
    components:{
        Intro,
        History,
        Companies,
        Weapon
    }
}
</script>

<style scoped>

</style>