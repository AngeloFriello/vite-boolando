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
        selectedProduct: {},
        open: false,
    }
  },
  methods: {
      showModal(product) {
        console.log('show modal')
        this.selectedProduct = product
        this.open = true
      },
      closeModal() {
        this.open = false
        this.selectedPasta = {}
      },
}
}
</script>

<template>
    <div class="container container-main">

        <div class="col-4" v-for="(product, i) in store.products" :key="i">
            <Card :product="product" @show="showModal"/>
        </div>
        <div v-if="open" class="modal">
            <div class="card">
                <div class="card__header">
                    {{ selectedProduct.name }}
                </div>
                <div class="card__body">

                </div>
            </div>
        </div>
    </div>
</template>

<style>
  
</style>