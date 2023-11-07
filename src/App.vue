<script>
    import BooleandoHeader from './components/BooleandoHeader.vue';
    import BooleandoMain from './components/BooleandoMain.vue';
    import BooleandoFooter from './components/BooleandoFooter.vue'; 

    export default {
        components:{
            BooleandoHeader,
            BooleandoMain,
            BooleandoFooter,
        },
        data() {
            return{
                
            }
        }
    }
</script>

<template>
    <header>
        <BooleandoHeader />

    </header>

    <main>
        <BooleandoMain />
    </main>

    <footer>
        <BooleandoFooter />
    </footer>
</template>

<style lang="scss">
    @use './styles/general.scss';
    @use './styles/partsials/variables.scss';
</style>


