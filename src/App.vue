<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  data() {
    return {
      menuItems: ["HOMES", "PAGES", "BLOG", "SHOP", "EVENTS", "ELEMENTS"],

      footerSections: [
        {
          title: "About",
          items: [
            "We created Everlead to effectively become the stepping stone towards meeting all your goals & achieving business success.",
          ],
          icons: [
            { class: "fa-brands fa-linkedin", label: "Icon 1" },
            { class: "fa-brands fa-facebook", label: "Icon 2" },
            { class: "fa-brands fa-square-twitter", label: "Icon 3" },
          ]
        },
        {
          title: "Twitter",
          items: [
            { 
            text: '@aliasadadm Hi @aliasadadm, can you please submit a ticket at https://t.co/JLV61aXG7d and one of our support agents... https://t.co/JLV61aXG7d', 
            twitter: true 
            },
            { 
            text: '@HenrySefaBoaky1 Check out our theme Gioia which has all necessary elements to build a multi vendor marketplace. https://t.co/c9BlYxZBlL', 
            twitter: true 
            },
          ]
        },
        {
          title: "Important links",
          items: [
            "About me",
            "About us",
            "Language packs",
            "Become a coach",
            "Monthly events",
          ]
        },
        {
          title: "Contact me",
          items: [
            "457 BigBlue Street, NY 10013",
            "(315) 5512-2579",
            "everlead@mikado.com",
          ]
        }
      ]
    };
  },
  components: {
    Header,
    Main,
    Footer
  }
};
</script>

<template>
  <div>
    <Header :items="menuItems" />
    <Main />
    <Footer :sections="footerSections" />
  </div>
</template>

<style lang="scss">
@use "./style/generals.scss";
</style>