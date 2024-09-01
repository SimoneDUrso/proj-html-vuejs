<script>
export default {
    
}
</script>

<template>
    <div>
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
    </div>
</template>
<style lang="scss" scoped>
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
            color: #BDBDBD;
        }
    }
}
</style>