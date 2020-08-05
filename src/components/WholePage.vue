<template>
    <div>
        <!-- Header -->
        <Header/>
        <!-- Main -->
        <MainContent/>
        <!-- Footer -->
        <Footer/>
    </div>
</template>

<script>
    import Header from './Header.vue'
    import Footer from './Footer.vue'
    import MainContent from './MainContent.vue'

export default {
    components:{
        Header,
        Footer,
        MainContent
    }
}
</script>

<style scoped>
    
</style>