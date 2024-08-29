<script>
export default {
    props: {
    sections: {
        type: Array,
        required: true
    }
    },
    methods: {
    isContactItem(item) {
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
            return "fa-regular fa-envelope";
        default:
            return "";
        }
    }
    }
};
</script>

<template>
    <footer class="footer-container">
        <div v-for="section in sections" :key="section.title" class="footer-section">
        <h3>{{ section.title }}</h3>
        <ul>
            <li v-for="item in section.items" :key="item.text || item">
            <!-- Mostra l'icona di Twitter solo se 'twitter' è true -->
            <i class="fa-brands fa-twitter" v-if="item.twitter"></i>

            <!-- Aggiungi icone specifiche per la sezione Contact me -->
            <i v-if="isContactItem(item)" :class="getIconClass(item)"></i>

            <!-- Visualizza il testo -->
            <span>{{ item.text || item }}</span>
        </li>
        </ul>
    </div>
    </footer>
</template>

<style lang="scss" scoped>
.footer-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.footer-section {
    flex: 1;
    min-width: 200px;
}

.footer-section h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.footer-section ul {
    list-style-type: none;
    padding: 0;
}

.footer-section ul li {
    margin-bottom: 5px;
    display: flex;
    align-items: center; /* Allinea l'icona e il testo */
}

.fa-twitter {
    margin-right: 8px;
    font-size: 16px;
    margin-top: 2px;
}

.footer-section ul li span {
    flex-grow: 1;
    line-height: 1.5; 
}
</style>