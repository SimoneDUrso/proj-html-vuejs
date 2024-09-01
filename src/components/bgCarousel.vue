<script>
export default {
    data() {
        return {
        images: [
            './src/assets/rev-slider-main-home-img-03.jpg',
            './src/assets/rev-slider-main-home-img-02.png',
        ],
        currentIndex: 0,
        };
    },

    methods:{
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
    }
</script>

<template>
    <div class="container-full d-flex flex-column justify-content-center"
                :style="{ backgroundImage: `url(${images[currentIndex]})` }" >
                <div class="row align-items-center">

                <!-- COLONNA CHE CONTIENE L'ARROW DI SINISTRA -->
                <div class="col-1 text-center fs-2">
                    <a href="#" @click.prevent="prevImage">
                        <i class="fa-solid fa-arrow-left-long text-dark"></i>
                    </a>
                </div>

                <!-- COLONNA CHE CONTIENE LE SCRITTE CENTRALI ED I PULSANTI -->
                <div class="col-10">
                    <span class="fw-bold">Our Team</span><span class="text-danger">.</span>
                    <p class="fs-5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi enim,
                    <br />
                    aliquam ipsam accusantium ad fugit adipisci?
                    </p>
                    <div class="d-flex">
                    <div class="me-5 d-flex bg-light p-2 pointer">
                        <div class="p-3 border-end border-dark read-more">READ MORE</div>
                        <div class="px-3 py-2 d-flex">
                        <i class="fa-solid fa-arrow-right-long text-dark"></i>
                        </div>
                    </div>

                    <div>
                        <div class="me-5 d-flex p-2 pointer purchase text-white">
                        <div class="p-3 border-end border-light read-more">PURCHASE</div>
                        <div class="px-3 py-2 d-flex text-white">
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </div>
                        </div>
                    </div>
            </div>
        </div>
        <!-- COLONNA CHE CONTIENE L'ARROW DI DESTRA -->
        <div class="col-1 text-center fs-2">
            <a href="#" @click.prevent="nextImage">
            <i class="fa-solid fa-arrow-right-long text-dark"></i>
            </a>
        </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.container-full{
    height: 900px;
    background-size: cover;
    background-position: center;
    transition: background-image 0.5s ease-in-out;

    .col-10{
        .purchase{
            background-color: #FF4612;
        }
        .pointer{
            cursor: pointer;
        }
        span{
            font-size: 100px;
        }
        p{
            color: #BDBDBD;
        }
        .read-more{
            height: 3px;
            display: flex;
            align-items: center;
        }
    }
}
</style>