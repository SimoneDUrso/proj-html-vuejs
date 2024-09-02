<script>
import bgCarousel from './bgCarousel.vue';
import imageSlider from './imageSlider.vue';
import fourthSection from './fourthSection.vue';
import latestNews from './latestNews.vue';
import creativeLeader from './creativeLeader.vue';
import testimonialsCarousel from './testimonialsCarousel.vue';

export default {
    components:{
        bgCarousel,
        imageSlider,
        fourthSection,
        latestNews,
        creativeLeader,
        testimonialsCarousel,
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
        <fourthSection />

        <!-- QUINTA SEZIONE -->
        <creativeLeader />

        <!-- SESTA SEZIONE -->
        <latestNews />

        <!-- SETTIMA SEZIONE -->
        <testimonialsCarousel />

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
main {
    height: 100%;
    overflow-x: hidden;

    .lorem {
        color: #BDBDBD;
    }

    .container-specialties.position-relative {
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
    .container-eighth-section {
        height: 900px;
        background-image: url(../assets/h1-img-04.jpg);
        background-size: cover;
        background-position: center;
        position: relative;

        .fa-arrow-up-long {
            right: 20px;
            top: 200px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px #888888;
            color: #FF4612;
        }

        .col-12 {
            font-size: 3rem;
            color: #fff;
        }
    }

    .container-ninth-section {
        height: 600px;
        width: 1200px;
        margin: 200px auto;

        .fa-arrow-up-long {
            right: -340px;
            top: -230px;
            font-size: 30px;
            background-color: white;
            padding: 10px;
            border-radius: 100%;
            box-shadow: 5px 10px 8px #888888;
            color: #FF4612;
        }

        .col-6.bg-world {
            background-image: url(../assets/h1-contact-rev-01.png);
            background-repeat: no-repeat;
            position: relative;

            .plus-1 {
                left: 150px;
                top: 100px;
            }

            .plus-2 {
                left: 300px;
                top: 70px;
            }

            .plus-3 {
                right: 100px;
                top: 230px;
            }

            .coaching {
                width: 300px;
                padding: 10px;
                background-color: white;
                bottom: 120px;
                right: 10px;

                .read-more {
                    height: 3px;
                    display: flex;
                    align-items: center;
                    cursor: pointer;
                }
            }
        }

        .col-6 {
            hr {
                border: none;
                height: 2px;
                width: 100px;
                color: #FF4612;
                background-color: #FF4612;
            }

            input {
                border: none;
                border-bottom: 2px solid #C0C0C0;
            }

            textarea {
                border: none;
                border-bottom: 2px solid #C0C0C0;
            }

            .purchase {
                background-color: #FF4612;
            }

            .pointer {
                cursor: pointer;
            }
        }

        .row-images {
            img{
                transition: 0.3s ease;
                &:hover{
                    filter: sepia(1) saturate(10000%) hue-rotate(-10deg) brightness(1) contrast(1);
                    cursor: pointer;
                }
            }
            
            .col-20 {
                width: 20%;

                .fa-arrow-up-long {
                    right: -330px;
                    top: 0px;
                    font-size: 30px;
                    background-color: white;
                    padding: 10px;
                    border-radius: 100%;
                    box-shadow: 5px 10px 8px #888888;
                    color: #FF4612;
                }
            }
        }
    }
    .read-more {
        position: relative;
        display: inline-flex;
        align-items: center;
        padding-right: 40px;
        cursor: pointer;
        transition: color 0.3s ease;
    }
    
    .read-more::after {
        content: "\f178";
        font-family: "Font Awesome 5 Free";
        font-weight: 900;
        font-size: 1rem;
        color: black;
        position: absolute;
        right: 150px;
        opacity: 0;
        transition: opacity 0.3s ease;
    }
    
    .read-more:hover::after {
        opacity: 1;
    }
}
</style>