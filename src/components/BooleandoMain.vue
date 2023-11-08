<script>
    import Card from './Card.vue'
    import Item from '../db.json'   
export default {
    components:{
        Card,
    },
  data() {
    return {
        products: Item.products,
    }
  }
}
</script>

<template>
    <div class="container container-main">

        <div class="col-4" v-for="(product, i) in products" :key="i">
            <Card :products="product" />
        </div>
        
    </div>
</template>

<style>

</style>