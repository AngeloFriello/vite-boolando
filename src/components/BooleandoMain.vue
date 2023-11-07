<script>
export default {
  data() {
    return {
      "products": [
    {
      "id": 1,
      "frontImage": "1.webp",
      "backImage": "1b.webp",
      "brand": "Levi's",
      "name": "Relaxed Fit",
      "price": 29.99,
      "isInFavorites": true,
      "badges": [
        {
          "type": "tag",
          "value": "Sostenibilità"
        },
        {
          "type": "discount",
          "value": "-50%"
        }
      ]
    },
    {
      "id": 2,
      "frontImage": "2.webp",
      "backImage": "2b.webp",
      "brand": "Guess",
      "name": "Roses Tee",
      "price": 20.99,
      "isInFavorites": true,
      "badges": [
        {
          "type": "discount",
          "value": "-30%"
        }
      ]
    },
    {
      "id": 3,
      "frontImage": "3.webp",
      "backImage": "3b.webp",
      "brand": "Come Zucchero Filato",
      "name": "Voglia di colori pastello",
      "price": 129.99,
      "isInFavorites": false,
      "badges": [
        {
          "type": "discount",
          "value": "-30%"
        }
      ]
    },
    {
      "id": 4,
      "frontImage": "4.webp",
      "backImage": "4b.webp",
      "brand": "Levi's",
      "name": "Tee Unisex",
      "price": 14.99,
      "isInFavorites": false,
      "badges": [
        {
          "type": "tag",
          "value": "Sostenibilità"
        },
        {
          "type": "discount",
          "value": "-50%"
        }
      ]
    },
    {
      "id": 5,
      "frontImage": "5.webp",
      "backImage": "5b.webp",
      "brand": "Maya Deluxe",
      "name": "Stripe Bodice",
      "price": 99.99,
      "isInFavorites": true,
      "badges": [
        {
          "type": "tag",
          "value": "Sostenibilità"
        },
        {
          "type": "discount",
          "value": "-50%"
        }
      ]
    },
    {
      "id": 6,
      "frontImage": "6.webp",
      "backImage": "6b.webp",
      "brand": "Esprit",
      "name": "Maglione - Black",
      "price": 29.99,
      "isInFavorites": true,
      "badges": [
        {
          "type": "tag",
          "value": "Sostenibilità"
        }
      ]
    },
  ]
    }
  }
}
</script>

<template>
    <div class="container container-main">
            <div class="col-4">
                <div>
                    <img src="../assets/1.webp" alt="" class="img-top">
                    <img src="../assets/1b.webp" alt="" class="img-back">
                    <div class="discount">-50%</div>
                    <div class="free">Sostenibilità</div>
                    <div class="heart">&hearts;</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>
            </div>
            <div class="col-4">
                <div>
                    <img src="../assets/2.webp" alt="" class="img-top">
                    <img src="../assets/2b.webp" alt="" class="img-back">
                    <div class="discount">-50%</div>
                    <div class="heart">&hearts;</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>
            </div>
            <div class="col-4">
                <div>
                    <img src="../assets/3.webp" alt="" class="img-top">
                    <img src="../assets/3b.webp" alt="" class="img-back">
                    <div class="discount">-50%</div>
                    <div class="heart">&hearts;</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>
            </div>

            <div class="col-4">
                <div>
                    <img src="../assets/4.webp" alt="" class="img-top">
                    <img src="../assets/4b.webp" alt="" class="img-back">
                    <div class="discount">-50%</div>
                    <div class="heart">&hearts;</div>
                    <div class="free">Sostenibilità</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>        
            </div>
            <div class="col-4">
                <div>
                    <img src="../assets/5.webp" alt="" class="img-top">
                    <img src="../assets/5b.webp" alt="" class="img-back">
                    <div class="heart">&hearts;</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>       
            </div>
            <div class="col-4">
                <div>
                    <img src="../assets/6.webp" alt="" class="img-top">
                    <img src="../assets/6b.webp" alt="" class="img-back">
                    <div class="heart">&hearts;</div>
                </div>
                <div>
                    <p class="brand">Levi's</p>
                    <p class="outfit-name">RELAXED FIT TEE UINISEX</p>
                    <p class="outfit-price">14,99</p>
                    <p class="outfit-price_discount">29,99</p>
                </div>      
            </div>
        </div>
</template>

<style>

</style>