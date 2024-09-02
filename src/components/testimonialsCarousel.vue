<script>
export default {
    
}
</script>

<template>
    <div>
        <div class="container-seventh-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row">
                <div class="col-12">
                    <h2 class="position-relative"><strong>Testimonials.</strong></h2>

                    <!-- Carosello -->
                    <div id="testimonialCarousel" class="carousel slide position-relative">
                        <div class="carousel-inner">
                            <!-- Primo profilo -->
                            <div class="carousel-item active">
                                <div class="d-flex flex-column align-items-center text-center">
                                    <img src="../assets/h3-img-04.png" class="d-block rounded-circle" alt="Testimonial 1">
                                    <p class="fw-bold fs-4 mt-4 text-white">Cynthia Clark</p>
                                    <p class="lorem fs-5">"lorem ipsum dolor sit amet, consectetur adipiscing elit sed eiusmod <br> tempor incididunt ut labore et dolore magna aliqua."</p>
                                    <div class="progress-bar-container">
                                        <div class="progress-bar">
                                            <div class="progress" style="width: 33%;"></div>
                                        </div>
                                        <span class="progress-label start">01</span>
                                        <span class="progress-label end">03</span>
                                    </div>
                                </div>
                            </div>
                            <!-- Secondo profilo -->
                            <div class="carousel-item">
                                <div class="d-flex flex-column align-items-center text-center">
                                    <img src="../assets/h3-img-07.png" class="d-block rounded-circle" alt="Testimonial 2">
                                    <p class="fw-bold fs-4 mt-4 text-white">Sarah Evans</p>
                                    <p class="lorem fs-5">"lorem ipsum dolor sit amet, consectetur adipiscing elit sed eiusmod <br> tempor incididunt ut labore et dolore magna aliqua."</p>
                                    <div class="progress-bar-container">
                                        <div class="progress-bar">
                                            <div class="progress" style="width: 66%;"></div>
                                        </div>
                                        <span class="progress-label start">01</span>
                                        <span class="progress-label end">03</span>
                                    </div>
                                </div>
                            </div>
                            <!-- Terzo profilo -->
                            <div class="carousel-item">
                                <div class="d-flex flex-column align-items-center text-center">
                                    <img src="../assets/h3-img-08.png" class="d-block rounded-circle" alt="Testimonial 3">
                                    <p class="fw-bold fs-4 mt-4 text-white">Jane Smith</p>
                                    <p class="lorem fs-5">"lorem ipsum dolor sit amet, consectetur adipiscing elit sed eiusmod <br> tempor incididunt ut labore et dolore magna aliqua."</p>
                                    <div class="progress-bar-container">
                                        <div class="progress-bar">
                                            <div class="progress" style="width: 100%;"></div>
                                        </div>
                                        <span class="progress-label start">01</span>
                                        <span class="progress-label end">03</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#testimonialCarousel" data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#testimonialCarousel" data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.container-seventh-section {
    height: 500px;
    background-color: #1E1E1E;
    padding: 0;
    position: relative;

    .fa-arrow-up-long {
        right: 20px;
        top: 80px;
        font-size: 30px;
        background-color: white;
        padding: 10px;
        border-radius: 100%;
        box-shadow: 5px 10px 8px #888888;
        color: #FF4612;
        z-index: 10000;
    }

    h2 {
        font-size: 200px;
        text-align: center;
        margin-top: -50px;
    }

    .carousel {
        top: -130px;
        .carousel-inner {
            .carousel-item {
                p {
                    color: #ccc;
                }
                .d-flex {
                    flex-direction: column;
                    align-items: center;
                    text-align: center;

                    img {
                        max-width: 150px;
                        margin-bottom: 1rem;
                    }

                    .fw-bold {
                        font-size: 1.5rem;
                    }

                    .lorem {
                        color: #BDBDBD;
                    }

                    .progress-bar-container {
                        width: 80%;
                        max-width: 300px;
                        position: relative;
                        margin-top: 1rem;
                    }

                    .progress-bar {
                        width: 100%;
                        background-color: #888888;
                        height: 4px;
                        border-radius: 4px;
                        position: relative;
                    }

                    .progress {
                        background-color: white;
                        height: 100%;
                        border-radius: 4px;
                        position: absolute;
                        top: 0;
                        left: 0;
                    }

                    .progress-label {
                        position: absolute;
                        color: #ccc;
                        font-size: 0.8rem;
                        top: -50%;
                        transform: translateY(-50%);
                    }

                    .progress-label.start {
                        left: -2rem;
                    }

                    .progress-label.end {
                        right: -2rem; 
                    }
                }
            }
        }

        .carousel-caption {
            bottom: 20px;
        }
    }
}
</style>