<script>
    import { store } from '../store'

    export default {
        props:{
            product:{
                type: Object,
                required: true,
            }
        },
        data(){
            return{
                store: store,
                protucts: store.products,
            }
        }
    }
</script>

<template>
        <div>
            <img :src="`../../public/${product.frontImage}`" alt="" class="img-top">
            <img :src="`../../public/${product.backImage}`" alt="" class="img-back">
            <div class="discount"></div>
            <div class="free"></div>
            <div class="heart">&hearts;</div>
        </div>
        <div>
            <p class="brand">{{ product.brand }}</p>
            <p class="outfit-name">{{ product.name }}</p>
            <p class="outfit-price">{{ product.price }}</p>
            <p class="outfit-price_discount">29,99</p>
        </div>
</template>

<style>

</style>