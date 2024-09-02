<script>
export default {
props: {
    items: Array
}
};
</script>

<template>
        <header>
            <div class="container-full px-5">
                <div class="row">
                <div class="col-6 pt-3">
                    <img src="../assets/logo-img-01.png" alt="Logo" class="w-25">
                </div>
                <div class="col-6 pt-3">
                    <nav>
                    <ul>
                        <li v-for="(item, index) in items" :key="index"><strong> {{ item }} </strong></li>
                        <li><i class="fa fa-search"></i></li>
                        <li><i class="fa fa-bars"></i></li>
                    </ul>
                    </nav>
                </div>
                </div>
            </div>
        </header>
</template>


<style lang="scss" scoped>
header {
    background-color: #fbfbfb;
    padding: 10px 0px;
    }

    nav {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    }

    ul {
    list-style: none;
    display: flex;
    gap: 15px;
    align-items: center;
    }

    li {
    display: flex;
    align-items: center;
    cursor: pointer;
    position: relative;
    padding-left: 25px;
    transition: color 0.3s ease;

    &:hover {
        color: #FF4612;
    }

    &::before {
        content: "\f178";
        font-family: "Font Awesome 5 Free";
        font-weight: 900;
        font-size: 1rem;
        color: #FF4612;
        position: absolute;
        left: 0;
        opacity: 0;
        transition: opacity 0.3s ease;
    }

    &:hover::before {
        opacity: 1;
    }
}

.fa {
    font-size: 1.1rem;
}
</style>