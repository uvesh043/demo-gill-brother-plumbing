<template>
  <div>
    <Header />
    <Content />
    <AboutUs />
    <!-- <Services /> -->
    <ServicesTwo/>
    <FormSection />
    <Footer />
  </div>
</template>
<script>
import Header from "../components/Header";
import Content from "../components/Content";
import AboutUs from "../components/AboutUs";
// import Services from "../components/Services.vue";
import ServicesTwo from "../components/ServicesTwo.vue";
import FormSection from "../components/FormSection.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Home",
  components: {
    Header,
    Content,
    AboutUs,
    // Services,
    ServicesTwo,
    FormSection,
    Footer,
  },
};
</script>

<style >
</style>