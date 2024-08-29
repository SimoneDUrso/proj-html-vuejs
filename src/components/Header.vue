<script>
export default {
props: {
    items: Array
}
};
</script>

<template>
        <header>
        <div class="container">
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
    background-color: #E1E1E1;
    padding: 10px;
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
    margin: 0px 5px;
}
.fa {
    font-size: 1.1rem;
}

</style>