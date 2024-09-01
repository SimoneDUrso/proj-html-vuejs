<script>
export default {
    
}
</script>

<template>
    <div>
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
                                                    <h6 class="card-subtitle mb-2 fw-bold fs-5">Melbourne Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 7, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none read-more fw-bold">READ MORE</a></p>
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
                                                    <h6 class="card-subtitle mb-2 fw-bold fs-5">New York Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 11, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none read-more fw-bold">READ MORE</a></p>
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
                                                    <h6 class="card-subtitle mb-2 fw-bold fs-5">London Coaching</h6>
                                                    <p class="card-text lorem"> <i class="fa-regular fa-clock"></i> 9:00 am - 5:00 pm, Jan 21, 2022 </p>
                                                    <p class="lorem"><i class="fa-solid fa-location-dot"></i> Cambridge, MA 02138, USA</p>
                                                    <p><a href="#" class="text-dark text-decoration-none read-more fw-bold">READ MORE</a></p>
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
    </div>
</template>
<style lang="scss" scoped>
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
    .lorem{
        color: #BDBDBD;
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
        right: 0px;
        opacity: 0;
        transition: opacity 0.3s ease;
    }
    
    .read-more:hover::after {
        opacity: 1;
    }
    h6:hover{
        color: #FF4612;
        cursor: pointer;
    }
}
</style>