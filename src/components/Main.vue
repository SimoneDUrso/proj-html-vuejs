<script>
import { onMounted } from 'vue';
import $ from 'jquery';
import 'slick-carousel/slick/slick.css';
import 'slick-carousel/slick/slick-theme.css';
import 'slick-carousel/slick/slick.js';
import bgCarousel from './bgCarousel.vue';
import imageSlider from './imageSlider.vue';

export default {
    components:{
        bgCarousel,
        imageSlider,
    },
};
</script>

<template>
        <main class="bg-light">
            <!-- PRIMA SEZIONE -->
            <bgCarousel />

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
        <imageSlider />

        <!-- QUARTA SEZIONE -->
        <div class="container-fourth-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row">
                <div class="col-12">
                    <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
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

        <!-- QUINTA SEZIONE -->
        <div class="container p-5 position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row p-5">
                <div class="col-6">
                    <span class="fw-bold fs-2">Creative Leader</span><span class="text-danger fw-bolder fs-2">.</span>
                    <hr>
                    <p class="lorem">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quia quisquam, nemo fugiat asperiores veniam molestiae accusamus facilis modi explicabo perferendis quasi quae, possimus id sed. Provident sit doloremque vitae consectetur!</p>
                    <div class="py-4 read-more fw-bold">
                        READ MORE
                    </div>
                </div>
        
                <div class="col-6">
                    <!-- Primo Blocco Mentorship -->
                    <div class="row border-bottom position-relative">
                        <div class="col-10 p-0">
                            <span class="fs-4"><strong>Mentorship</strong></span>
                        </div>
                        <div class="col-2 pb-2 text-end">
                            <span class="fs-4"><strong>78%</strong></span>
                        </div>
                        <!-- Barra di percentuale -->
                        <div class="percent-bar" style="width: 78%;"></div>
                    </div>
        
                    <!-- Secondo Blocco Education -->
                    <div class="row border-bottom position-relative my-4">
                        <div class="col-10 p-0">
                            <span class="fs-4"><strong>Education</strong></span>
                        </div>
                        <div class="col-2 pb-2 text-end">
                            <span class="fs-4"><strong>95%</strong></span>
                        </div>
                        <!-- Barra di percentuale -->
                        <div class="percent-bar" style="width: 95%;"></div>
                    </div>
        
                    <!-- Terzo Blocco Learning -->
                    <div class="row border-bottom position-relative my-4">
                        <div class="col-10 p-0">
                            <span class="fs-4"><strong>Learning</strong></span>
                        </div>
                        <div class="col-2 pb-2 text-end">
                            <span class="fs-4"><strong>65%</strong></span>
                        </div>
                        <!-- Barra di percentuale -->
                        <div class="percent-bar" style="width: 65%;"></div>
                    </div>
        
                    <!-- Quarto Blocco Motivation -->
                    <div class="row border-bottom position-relative">
                        <div class="col-10 p-0">
                            <span class="fs-4"><strong>Motivation</strong></span>
                        </div>
                        <div class="col-2 pb-2 text-end">
                            <span class="fs-4"><strong>83%</strong></span>
                        </div>
                        <!-- Barra di percentuale -->
                        <div class="percent-bar" style="width: 83%;"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- SESTA SEZIONE -->
        <div class="container-sixth-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row">
                <div class="col-12 text-center pt-5">
                    <span class="fw-bold fs-2">Latest News</span><span class="text-danger fw-bold fs-2">.</span>
                    <p class="lorem fs-4">Lorem, ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <div class="d-flex justify-content-center">
                        <hr>
                    </div>
                </div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-md-1 d-flex align-items-center fs-2">
                        <a href="#"><i class="fa-solid fa-arrow-left-long text-dark"></i></a>
                    </div>
                    <!-- Prima News -->
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <div class="double-img">
                                    <img src="../assets/h1-blog-img-02.jpg" class="img-1" alt="Next investment">
                                    <img src="../assets/h1-blog-img-03.jpg" class="img-2" alt="">
                                    <div class="business-leading position-absolute">
                                        <span><i class="fa-solid fa-tag"></i> Business, Leading</span>
                                    </div>
                            </div>
                            <div class="card-body mt-5">
                                <p class="card-title lorem"><i class="fa-regular fa-clock"></i> May 5, 2019 <i class="fa-regular fa-user"></i> Amanda Doe</p>
                                <h3 class="card-text">Next investment</h3>
                                <p class="lorem"> Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                                <div class="read-more fw-bold">
                                    READ MORE
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- Seconda News -->
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <div class="double-img">
                                    <img src="../assets/h1-blog-img-03.jpg" class="img-1" alt="Next investment">
                                    <img src="../assets/h1-blog-img-04.jpg" class="img-2" alt="">
                                    <div class="business-leading position-absolute">
                                        <span><i class="fa-solid fa-tag"></i> Business, Leading</span>
                                    </div>
                            </div>
                            <div class="card-body mt-5">
                                <p class="card-title lorem"><i class="fa-regular fa-clock"></i> May 5, 2019 <i class="fa-regular fa-user"></i> Amanda Doe</p>
                                <h3 class="card-text">Team Building</h3>
                                <p class="lorem"> Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                                <div class="read-more fw-bold">
                                    READ MORE
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- Terza News -->
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <div class="double-img">
                                    <img src="../assets/h1-blog-img-04.jpg" class="img-1" alt="Next investment">
                                    <img src="../assets/h1-blog-img-01.jpg" class="img-2" alt="">
                                    <div class="business-leading position-absolute">
                                        <span><i class="fa-solid fa-tag"></i> Business, Leading</span>
                                    </div>
                            </div>
                            <div class="card-body mt-5">
                                <p class="card-title lorem"><i class="fa-regular fa-clock"></i> May 5, 2019 <i class="fa-regular fa-user"></i> Amanda Doe</p>
                                <h3 class="card-text">New Business Day</h3>
                                <p class="lorem"> Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                                <div class="read-more fw-bold">
                                    READ MORE
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-1 d-flex align-items-center justify-content-end fs-2">
                        <a href="#"><i class="fa-solid fa-arrow-right-long text-dark"></i></a>
                    </div>
                </div>
            </div>
        </div>

        <!-- SETTIMA SEZIONE -->
        <div class="container-seventh-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row">
                <div class="col-12">
                    <h2 class="position-relative"><strong>Testimonials.</strong></h2>
                    <div class="container-testimonials position-absolute">
                        <div class="row text-white">
                            <div class="col-2 d-flex align-items-center justify-content-start">
                                <button class="btn btn-md text-white fs-2"><i class="fa-solid fa-arrow-left-long"></i></button>
                            </div>
        
                            <div class="col-8 text-center">
                                <img src="../assets/h3-img-04.png" alt="">
                                <p class="fw-bold fs-4 mt-4">Cynthia Clark</p>
                                <p class="lorem fs-5">"Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                                    Non quia, temporibus nemo tenetur sapiente doloribus expedita ducimus architecto 
                                    tempore in qui odio quasi omnis inventore sint perspiciatis id quam animi?"</p>
                                    
                                <!-- BARRA DI PROGRESSIONE DEI PROFILI -->
                                <div class="progress-bar-container mt-4 d-flex align-items-center justify-content-center w-25">
                                    <span class="progress-bar-start">01</span>

                                    <div class="progress-bar">
                                        <div class="progress">

                                        </div>
                                    </div>
                                    
                                    <span class="progress-bar-end">03</span>
                                </div>
                            </div>
        
                            <div class="col-2 d-flex align-items-center justify-content-end fs-2">
                                <button class="btn btn-md text-white fs-2"><i class="fa-solid fa-arrow-right-long"></i></button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- OTTAVA SEZIONE -->
        <div class="container-eighth-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute arrow-up-2"></i></a>
            <div class="row h-100 d-flex align-items-center justify-content-center">
                <div class="col-12 text-center">
                    
                    <i class="fa-solid fa-play"></i>
                </div>
            </div>
        </div>

        <!-- NONA SEZIONE -->
        <div class="container-ninth-section position-relative">
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
            <div class="row h-100">
                <div class="col-6 bg-world d-flex justify-content-center align-items-center">
                    <img src="../assets/h1-contact-rev-02.png" alt="" class="position-absolute plus-1">
                    <img src="../assets/h1-contact-rev-02.png" alt="" class="position-absolute plus-2">
                    <img src="../assets/h1-contact-rev-02.png" alt="" class="position-absolute plus-3">
                    <div class="position-relative coaching">
                        <h3>New York Coaching</h3>
                        <p class="read-more fw-bold">READ MORE</p>
                    </div>
                </div>
                <div class="col-6">
                    <span class="fw-bold fs-1">Contact us</span><span class="text-danger fw-bold fs-1">.</span>
                    <p class="lorem fs-4"> Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
                    <hr>
                    <div class="d-flex">
                        <input type="text" placeholder="Your Name" class="form-control me-3">
                        <input type="email" placeholder="Your Email" class="form-control ms-3">
                    </div>
                    <textarea placeholder="Write a message..." class="form-control mt-2" rows="5" cols="50"></textarea>
                    <div class="me-5 d-flex p-2 pointer purchase text-white w-25 mt-4">
                        <div class="p-3 border-end border-light">
                            SEND
                        </div>
                        <div class="px-3 py-2 d-flex text-white d-flex align-items-center">
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </div>
                    </div>
                </div>
            </div>
        
            <!-- Seconda riga con immagini -->
            <div class="row row-images">
                <div class="col-20 d-flex justify-content-center">
                    <img src="../assets/h4-clients-img-03.png" alt="">
                </div>
                <div class="col-20 d-flex justify-content-center">
                    <img src="../assets/h4-clients-img-05.png" alt="">
                </div>
                <div class="col-20 d-flex justify-content-center">
                    <img src="../assets/h4-clients-img-07.png" alt="">
                </div>
                <div class="col-20 d-flex justify-content-center">
                    <img src="../assets/h4-clients-img-09.png" alt="">
                </div>
                <div class="col-20 d-flex justify-content-center position-relative">
                    <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
                    <img src="../assets/h4-clients-img-01.png" alt="">
                </div>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main{
    height: 100%;
    overflow-x: hidden;

    
    .lorem{
        color: #BDBDBD;
    }
    .container.my-5.position-relative{
        .fa-arrow-up-long{
            right: -280px;
            top: -150px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }
    }

    .container-specialties.position-relative{
        width: 1800px;
        margin: 0 auto;
        top: -70px;
        background-color: white;
        hr {
            border: none;
            height: 2px;
            width: 50px;
            color: #FF4612;
            background-color: #FF4612;
        }
    }

    .container-fourth-section{
        background-image: url(../assets/h1-img-09.jpg);
        padding-bottom: 140px;
        margin: 50px 0px;

        .fa-arrow-up-long{
            right: 20px;
            top: -80px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }

        .col-12{
            .fa-arrow-up-long{
                right: 20px;
                top: 50%;
                font-size: 30px;
                background-color: white;
                padding: 10px;
                border-radius: 100%;
                box-shadow: 5px 10px 8px  #888888;
                color: #FF4612;
            }
        }
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

    .container.p-5 {
        .fa-arrow-up-long{
            right: -280px;
            top: 50%;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }
        .col-6{
            hr {
                border: none;
                height: 2px;
                width: 100px;
                color: #FF4612;
                background-color: #FF4612;
            }
            .read-more{
                height: 3px;
                display: flex;
                align-items: center;
                cursor: pointer;
            }
            .percent-bar {
                position: absolute;
                bottom: -2px;
                left: 0;
                height: 4px;
                background-color: #dc3545;
            }
            .lorem{
                font-size: 18px;
            }
        }
    }

    .container-sixth-section{
        background-color: #e1e1e167;
        height: 800px;

        .fa-arrow-up-long{
            right: 20px;
            top: 50%;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }

        hr{
                border: none;
                height: 2px;
                width: 100px;
                color: #FF4612;
                background-color: #FF4612;
        }
    }
    .img-bot{
        bottom: 100px;
    }
    .col-md-3 {
        .double-img{
            height: 240px;
            position: relative;

            .business-leading{
                right: 10px;
                bottom: -30px;
                background-color: #FF4612;
                padding: 10px 30px;
                color: #E1E1E1;
            }

            .img-1, .img-2{
                position: absolute;
            }
            .img-1{
                width: 100%;
            }
            .img-2{
                top: 80px;
                width: 100%;
                height: 180px;
                object-fit: cover;
                object-position: bottom;
            }
        }
        .card{
            min-height: 400px;
            background-color: #e1e1e100;
            border: none;
            
            .card-body{
                background-color: #e1e1e100;
                border: none;

                .read-more{
                    height: 3px;
                    display: flex;
                    align-items: center;
                    cursor: pointer;
                }

                .fa-regular{
                    color: #FF4612;
                }
            }

        }
    }
    .container-seventh-section{
        height: 500px;
        background-color: #1E1E1E;
        padding: 0;

        .fa-arrow-up-long{
            right: 20px;
            top: 80px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
            z-index: 10000;
        }

        h2{
            font-size: 200px;
            text-align: center;
            top: -50px;
        }

        .col-12{
            z-index: 1;

            .container-testimonials{
                width: 1600px;
                z-index: 10;
                left: 50%;
                top: 50%;
                transform: translate(-50%, -50%);

                .col-8{
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    flex-direction: column;

                    .progress-bar-container {
                        width: 100%;
                    }
                    
                    .progress-bar {
                        flex-grow: 1;
                        height: 3px; 
                        background-color: #ccc; 
                        margin: 0 10px;
                        position: relative;
                        border-radius: 3px;
                    }
                    
                    .progress {
                        width: 33%;
                        height: 100%;
                        background-color: #fff;
                        position: absolute;
                        top: 0;
                        left: 0;
                        border-radius: 3px;
                    }
                    
                    .progress-bar-start,
                    .progress-bar-end {
                        font-weight: bold;
                        font-size: 1rem;
                    }
                }
            }
        }
    }
    .container-eighth-section{
        height: 900px;
        background-image: url(../assets/h1-img-04.jpg);
        background-size: cover;
        background-position: center;
        position: relative;

        .fa-arrow-up-long{
            right: 20px;
            top: 200px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }

    .col-12 {
        font-size: 3rem;
        color: #fff;
        
    }
}
    .container-ninth-section{
        height: 600px;
        width: 1200px;
        margin: 200px auto;

        .fa-arrow-up-long{
            right: -340px;
            top: -230px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px  #888888;
            color: #FF4612;
        }
        
        .col-6.bg-world{
            background-image: url(../assets/h1-contact-rev-01.png);
            background-repeat: no-repeat;
            position: relative;
            .plus-1{
                left: 150px;
                top: 100px;
            }

            .plus-2{
                left: 300px;
                top: 70px;
            }

            .plus-3{
                right: 100px;
                top: 230px;
            }
            .coaching{
                width: 300px;
                padding: 10px;
                background-color: white;
                bottom: 120px;
                right: 10px;

                .read-more{
                    height: 3px;
                    display: flex;
                    align-items: center;
                    cursor: pointer;
                }

            }
        }
        .col-6{
            hr {
                border: none;
                height: 2px;
                width: 100px;
                color: #FF4612;
                background-color: #FF4612;
            }
            input{
                border: none;
                border-bottom: 2px solid #C0C0C0;
            }
            textarea{
                border: none;
                border-bottom: 2px solid #C0C0C0;
            }
            .purchase{
                background-color: #FF4612;
            }
            .pointer{
                cursor: pointer;
            }
        }
        .row-images{
            
            .col-20{
                width: 20%;

                .fa-arrow-up-long{
                    right: -330px;
                    top: 0px;
                    font-size: 30px;
                    background-color: white;
                    padding: 10px;
                    border-radius: 100%;
                    box-shadow: 5px 10px 8px  #888888;
                    color: #FF4612;
                }
            }
        }
    }
}
</style>