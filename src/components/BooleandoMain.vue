<script>
    import Card from './Card.vue';  
    import { store } from '../store'
export default {
    components:{
        Card,
    },
  data() {
    return {
        store,
    }
  }
}
</script>

<template>
    <div class="container container-main">

        <div class="col-4" v-for="(product, i) in store.products" :key="i">
            <Card :product="product" />
        </div>
        
    </div>
</template>

<style>

</style>