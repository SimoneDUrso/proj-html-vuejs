<script>
import { onMounted } from 'vue';
import $ from 'jquery';
import 'slick-carousel/slick/slick.css';
import 'slick-carousel/slick/slick-theme.css';
import 'slick-carousel/slick/slick.js';

export default {
    methods: {
        prevImage() {
        this.currentIndex =
            this.currentIndex > 0
            ? this.currentIndex - 1
            : this.images.length - 1;
        },
        nextImage() {
        this.currentIndex =
            this.currentIndex < this.images.length - 1
            ? this.currentIndex + 1
            : 0;
        },
    },
    name: 'ImageSlider',
    mounted() {
        // Inizializzazione dello slider su '.single-item'
        $('.single-item').slick({
        dots: true,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        arrows: false, // Disabilita le frecce di default di Slick
        });

        // Controllo custom delle frecce
        $('.custom-prev').on('click', function(event) {
      event.preventDefault(); // Previene lo scroll della pagina
        $('.single-item').slick('slickPrev');
        });

        $('.custom-next').on('click', function(event) {
        event.preventDefault(); // Previene lo scroll della pagina
        $('.single-item').slick('slickNext');
        });
    },
}
</script>

<template>
    <div>
        <div class="container my-5 position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row">
                <div class="col-7 position-relative p-0">

                    <!-- Contenitore per lo slider -->
                    <div class="single-item">
                    <div>
                        <img src="../assets/h1-blog-img-04.jpg" alt="Image 1" class="img-fluid">
                    </div>
                    <!-- Qui aggiungo le altre immagini che verranno slidate -->
                    <div>
                        <img src="../assets/h1-blog-img-02.jpg" alt="Image 2" class="img-fluid">
                    </div>
                    <div>
                        <img src="../assets/h1-blog-img-03.jpg" alt="Image 3" class="img-fluid">
                    </div>
                    </div>
            
                    <div class="orange-section position-absolute py-4 px-5">
                    <!-- Utilizzo delle tue icone personalizzate per la navigazione -->
                    <a href="#" class="custom-prev"><i class="fa-solid fa-arrow-left-long me-3 fs-2" style="color: #ffffff;"></i></a>
                    <a href="#" class="custom-next"><i class="fa-solid fa-arrow-right-long fs-2" style="color: #ffffff;"></i></a>
                    </div>
                </div>
            
                <div class="col-5">
                    <div class="container-jason px-4 py-5 fw-bold">
                    <h2>Jason Bickford</h2>
                    <p class="lorem fs-5">Founder and executive director</p>
                    <hr>
                    <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, amet sapiente! Eaque hic repudiandae, deleniti a totam excepturi dolorum officia cumque perferendis, aperiam minima quo accusamus itaque expedita consequatur eligendi.</p>
                    <a href="#"><i class="fa-brands fa-linkedin fs-3"></i></a>
                    <a href="#"><i class="fa-brands fa-facebook fs-3 mx-3"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter fs-3"></i></a>
                    <span>Jason Brick</span>
                    </div>
                </div>
                </div>
            </div>
    </div>
</template>
<style lang="scss" scoped>
.container .col-5{
    background-image: url(../assets/svg-4.svg);
    position: relative;
    bottom: 20px;
    left: 300px;

    .container-jason{
        width: 800px;
        height: 400px;
        background-color: white;
        position: relative;
        top: 80px;
        right: 450px;

        hr {
            border: none;
            height: 2px;
            width: 100px;
            color: #FF4612;
            background-color: #FF4612;
        }
        .fa-brands{
            color: #FF4612;
        }
        span{
            font-family: "Alex Brush", cursive;
            font-size: 50px;
            margin-left: 300px;
            color: #FF4612;
        }
    }
}
.fa-arrow-up-long{
    right: -280px;
    top: -160px;
    font-size: 30px;
    background-color: white;
    padding: 10px;
    border-radius: 100%;
    box-shadow: 5px 10px 8px  #888888;
    color: #FF4612;
}
    /* Assicura che le immagini siano stilizzate correttamente per lo slider */
.single-item {
width: 100%;
overflow: hidden;
}

.single-item img {
width: 100%;
height: auto;
}

.slick-slide {
display: flex;
justify-content: center;
align-items: center;
}

.slick-prev, .slick-next {
position: absolute;
top: 50%;
transform: translateY(-50%);
z-index: 10;
cursor: pointer;
}

.slick-prev {
left: 10px;
}

.slick-next {
right: 10px;
}
.container .orange-section{
    left: 0;
    bottom: 35px;
    background-color: #FF4612;
}
</style>