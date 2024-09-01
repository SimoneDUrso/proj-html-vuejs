<script>
export default {
    
}
</script>

<template>
    <div>
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
    </div>
</template>
<style lang="scss" scoped>
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
        .lorem{
            color: #BDBDBD;
        }
    }
}
</style>