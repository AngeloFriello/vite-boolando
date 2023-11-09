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
        this.selectedProduct = {}
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
                <font-awesome-icon :icon="['fas', 'circle-xmark']" />
                <div class="card-header">
                    {{ selectedProduct.name}}
                </div>
                <div class="card-body">
                    {{ selectedProduct.brand }}
                </div>
            </div>
        </div>
    </div>
</template>

<style>
  
</style>