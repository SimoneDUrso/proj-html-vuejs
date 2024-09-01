<script>
export default {
    props: {
    sections: Array
    },

    methods: {
    ContactItem(item) {
        // Verifica se l'elemento è nella sezione "Contact me"
        return item === "457 BigBlue Street, NY 10013" ||
                item === "(315) 5512-2579" ||
                item === "everlead@mikado.com";
    },
    getIconClass(item) {
        // Ritorna la classe dell'icona basata sul contenuto dell'elemento
        switch (item) {
        case "457 BigBlue Street, NY 10013":
            return "fa-solid fa-location-dot";
        case "(315) 5512-2579":
            return "fa-solid fa-phone";
        case "everlead@mikado.com":
            return "fa-solid fa-envelope";
        default:
            return "";
        }
    }
    }
};
</script>

<template>
    <footer>
        <div class="footer-container">
            <div v-for="section in sections" :key="section.title" class="footer-section">
                <h3>{{ section.title }}</h3>
                <hr>
                <ul>
                    <li v-for="item in section.items" :key="item.text || item">
                        
                        <!-- Mostra l'icona di Twitter solo se 'twitter' è true -->
                        <i class="fa-brands fa-twitter" v-if="item.twitter"></i>
    
                        <!-- Aggiungi icone specifiche per la sezione Contact me -->
                        <i v-if="ContactItem(item)" :class="getIconClass(item)"></i>
    
                        <!-- Visualizza il testo -->
                        <span>{{ item.text || item }}</span>
                    </li>
                    <div class="about-icons">
                        <i v-for="icon in section.icons" :class="icon.class" :key="icon.label"></i>
                    </div>
                </ul>
            </div>
        </div>
        <div class="footer-bottom text-center position-relative">
            Copyright Everlead©MikadoThemes
            <a href="#"><i class="fa-solid fa-arrow-up-long position-absolute"></i></a>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
.footer-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    background-color: #1E1E1E;
    color: #CCCCCC;
    padding: 50px;
}

.footer-section {
    flex: 1;
    min-width: 200px;
}

.footer-section h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

hr {
    border: none;
    height: 2px;
    width: 50px;
    color: #FF4612;
    background-color: #FF4612;
    margin-bottom: 20px;
}

.footer-section ul {
    list-style-type: none;
    padding: 0;
}

.footer-section ul li {
    margin-bottom: 5px;
    display: flex;
    align-items: start;
}

.footer-section ul li i {
    margin-right: 8px;
    font-size: 16px;
    line-height: 1;
    color: #FF4612;
}

.about-icons {
    margin-top: 10px;
}

.about-icons i {
    font-size: 20px;
    margin-right: 15px;
    color: white;
}

.footer-bottom {
    background-color: #FF4612;
    color: #CCCCCC;
    padding: 5px 0px;

    .fa-arrow-up-long {
        right: 20px;
        bottom: 10px;
        font-size: 30px;
        background-color: white;
        padding: 10px;
        border-radius: 100%;
        box-shadow: 5px 10px 8px #888888;
        color: #FF4612;
    }
}
</style>