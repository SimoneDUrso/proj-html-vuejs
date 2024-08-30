<script>
export default {
    
}
</script>

<template>
    <main class="bg-light">
        <!-- CONTAINER PER LA PRIMA SEZIONE -->
        <div class="container-full d-flex flex-column justify-content-center">
            <div class="row align-items-center">
                <!-- COLONNA CHE CONTIENE L'ARROW DI SINISTRA -->
                <div class="col-1 text-center fs-2">
                    <a href="#"><i class="fa-solid fa-arrow-left-long text-dark"></i></a>
                </div>
                <!-- COLONNA CHE CONTIENE LE SCRITTE CENTRALI ED I PULSANTI -->
                <div class="col-10">
                    <span class="fw-bold">Our Team</span><span class="text-danger">.</span>
                    <p class="fs-5">Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Modi enim, <br>
                        aliquam ipsam accusantium ad fugit adipisci?</p>
                        <div class="d-flex">
                            <div class="me-5 d-flex bg-light p-2 pointer">
                                <div class="p-3 border-end border-dark read-more">
                                    READ MORE
                                </div>
                                <div class="px-3 py-2 d-flex">
                                    <i class="fa-solid fa-arrow-right-long text-dark"></i>
                                </div>
                            </div>

                            <div>
                                <div class="me-5 d-flex p-2 pointer purchase text-white">
                                <div class="p-3 border-end border-light read-more">
                                    PURCHASE
                                </div>
                                <div class="px-3 py-2 d-flex text-white">
                                    <i class="fa-solid fa-arrow-right-long"></i>
                                </div>
                            </div>
                            </div>
                        </div>
                </div>
                <!-- COLONNA CHE CONTIENE L'ARROW DI DESTRA -->
                <div class="col-1 text-center fs-2">
                    <a href="#"><i class="fa-solid fa-arrow-right-long text-dark"></i></a>
                </div>
            </div>
        </div>

        <!-- SECONDA SEZIONE -->
        <div class="container-specialties position-relative p-4">
            <div class="text-center">
                <span class="fw-bold fs-2">Our Specialties</span><span class="text-danger fw-bolder fs-2">.</span>
                <p class="lorem fs-4">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <div class="d-flex justify-content-center">
                    <hr>
                </div>
            </div>
            <div class="row">
                <div class="col-3 text-center">
                    <img src="../assets/svg-0.svg" alt="">
                    <p class="fs-2"><strong>Knowing</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-1.svg" alt="">
                    <p class="fs-2"><strong>Selling</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-2.svg" alt="">
                    <p class="fs-2"><strong>Learning</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-3.svg" alt="">
                    <p class="fs-2"><strong>Contact</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </div>

        <!-- TERZA SEZIONE -->
    </main>
</template>
<style lang="scss" scoped>
main{
    height: 100%;

    .container-full{
        height: 800px;
        background-image: url(../assets/rev-slider-main-home-img-03.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;

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
    .lorem{
        color: #BDBDBD;
    }
    hr {
        border: none;
        height: 2px;
        width: 50px;
        color: red;
        background-color: red;
    }

    .container-specialties.position-relative{
        width: 1800px;
        margin: 0 auto;
        top: -40px;
        background-color: white;
    }
}
</style>