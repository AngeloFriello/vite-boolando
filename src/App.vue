<script>
    import BooleandoHeader from './components/BooleandoHeader.vue';
    import BooleandoMain from './components/BooleandoMain.vue';
    import BooleandoFooter from './components/BooleandoFooter.vue';
    import { store } from './store.js';

    export default {
        components:{
            BooleandoHeader,
            BooleandoMain,
            BooleandoFooter,
        },
        data() {
            return{
                store: store,
            }
        },
        // created(){
        //     axios.get()
        //     .then(res=>{
        //         const paste = res.data
        //         this.store.products = products
        //     })
        // },
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


