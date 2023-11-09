<script>
    import BooleandoHeader from './components/BooleandoHeader.vue';
    import BooleandoMain from './components/BooleandoMain.vue';
    import BooleandoFooter from './components/BooleandoFooter.vue';
    import { faCircleXmark } from '@fortawesome/free-regular-svg-icons'
    import { store } from './store.js';
    import axios from 'axios';

    export default {
        components:{
            BooleandoHeader,
            BooleandoMain,
            BooleandoFooter,
        },
        data() {
            return{
                store: store,
                productsUrl:'http://localhost:3000/products'
            }
        },
        created(){
            axios.get(this.productsUrl)
            .then(res=>{
                const products = res.data
                this.store.products = products
            })
        },
    } 
</script>

<template>
    <body id="app">
        <header>
        <BooleandoHeader />

    </header>

    <main>
        <BooleandoMain />
    </main>

    <footer>
        <BooleandoFooter />
    </footer>
    </body>
</template>

<style lang="scss">
    @use './styles/general.scss';
    @use './styles/partsials/variables.scss';
</style>


