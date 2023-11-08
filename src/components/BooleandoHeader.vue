<script>
    import { store } from '../store';

    export default {
      data() {
        return {
            store,
          title: 'Footer'
        }
      }
    }
</script>

<template>
    <nav class="nav-header">    
        <div class="container">
            <div class="col-12">
                <div>
                    <a href="">Donna</a>
                    <a href="">Uomo</a>
                    <a href="">Bambini</a>
                </div>
                <div>
                    <img src="../../public/boolean-logo.png" alt="" class="logo">
                </div>
                <div>
                    <ul class="icon">
                        <li><a href=""><i class="fa-brands fa-facebook"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-twitter"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-instagram"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-telegram"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
</template>

<style>

</style>