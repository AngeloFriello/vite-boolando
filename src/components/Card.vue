<script>
    export default {
        data() {
            return {
                props:{
                    product:{
                        type: Object,
                        required: true,
                    }
                }
            }
        }
    }
</script>

<template>
        <div>
            <img src="../assets/1.webp" alt="" class="img-top">
            <img src="../assets/1b.webp" alt="" class="img-back">
            <div class="discount">-50%</div>
            <div class="free">Sostenibilità</div>
            <div class="heart">&hearts;</div>
        </div>
        <div>
            <p class="brand">Levi's</p>
            <p class="outfit-name">{{ product.name }}</p>
            <p class="outfit-price">14,99</p>
            <p class="outfit-price_discount">29,99</p>
        </div>
</template>

<style>

</style>