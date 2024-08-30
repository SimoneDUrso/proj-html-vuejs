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
                    <p class="fs-3"><strong>Knowing</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-1.svg" alt="">
                    <p class="fs-3"><strong>Selling</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-2.svg" alt="">
                    <p class="fs-3"><strong>Learning</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
                <div class="col-3 text-center">
                    <img src="../assets/svg-3.svg" alt="">
                    <p class="fs-3"><strong>Contact</strong></p>
                    <p class="lorem fs-5">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </div>

        <!-- TERZA SEZIONE -->
        <div class="container my-5">
            <div class="row">
                <div class="col-7 position-relative p-0">
                    <img src="../assets/h1-blog-img-04.jpg" alt="" class="img-fluid">
                    <div class="orange-section position-absolute py-4 px-5">
                        <a href=""><i class="fa-solid fa-arrow-left-long me-3 fs-2" style="color: #ffffff;"></i></a>
                        <a href=""><i class="fa-solid fa-arrow-right-long fs-2" style="color: #ffffff;"></i></a>
                    </div>
                </div>

                <div class="col-5">
                    <div class="container-jason px-4 py-5 fw-bold">
                        <h2>Jason Bickford</h2>
                        <p class="lorem fs-5">Founder and executive director</p>
                        <hr>
                        <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, amet sapiente! Eaque hic repudiandae, deleniti a totam excepturi dolorum officia cumque perferendis, aperiam minima quo accusamus itaque expedita consequatur eligendi.</p>
                        <a href=""><i class="fa-brands fa-linkedin fs-3"></i></a>
                        <a href=""><i class="fa-brands fa-facebook fs-3 mx-3"></i></a>
                        <a href=""><i class="fa-brands fa-square-twitter fs-3"></i></a>
                        <span>Jason Brick</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- QUARTA SEZIONE -->
        <div class="container-fourth-section">
            <div class="row">
                <div class="col-12">
                    <div class="container-cards">
                        <div class="card" style="width: 28rem;">
                            <div class="card-header fs-3 fw-bold">
                                Upcoming Events
                            </div>
                            <ul class="list-group list-group-flush">
                                <div class="card" style="width: 28rem;">
                                    <div class="card-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-4">
                                                    <div class="orange-square">
                                                        <p class="fw-bold text-white">07</p>
                                                        <p class="lorem">Jan, 2022</p>
                                                    </div>
                                                </div>
                                                <div class="col-8">
                                                    <h6 class="card-subtitle mb-2 text-body-secondary fw-bold fs-5">Melbourne Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 7, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none fw-bold">READ MORE</a></p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
    
                                <div class="card" style="width: 28rem;">
                                    <div class="card-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-4">
                                                    <div class="orange-square">
                                                        <p class="fw-bold text-white">11</p>
                                                        <p class="lorem">Jan, 2022</p>
                                                    </div>
                                                </div>
                                                <div class="col-8">
                                                    <h6 class="card-subtitle mb-2 text-body-secondary fw-bold fs-5">New York Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 11, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none fw-bold">READ MORE</a></p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
    
                                <div class="card" style="width: 28rem;">
                                    <div class="card-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-4">
                                                    <div class="orange-square">
                                                        <p class="fw-bold text-white">21</p>
                                                        <p class="lorem">Jan, 2022</p>
                                                    </div>
                                                </div>
                                                <div class="col-8">
                                                    <h6 class="card-subtitle mb-2 text-body-secondary fw-bold fs-5">London Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 21, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none fw-bold">READ MORE</a></p>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
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
    

    .container-specialties.position-relative{
        width: 1800px;
        margin: 0 auto;
        top: -40px;
        background-color: white;
        hr {
            border: none;
            height: 2px;
            width: 50px;
            color: #FF4612;
            background-color: #FF4612;
        }
    }

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
    .container .orange-section{
        left: 0;
        bottom: 0;
        background-color: #FF4612;
    }

    .container-fourth-section{
        background-image: url(../assets/h1-img-09.jpg);
        height: 900px;
        margin: 50px 0px;
    }
    .container-cards{
        width: 1200px;
        margin: 0 auto;
        margin-top: 100px;

        .orange-square{
            padding: 10px 0px;
            background-color: #FF4612;
            text-align: center;
            height: 80px;
        }

        .fa-regular, .fa-solid{
            color: #FF4612;
        }
    }
}
</style>