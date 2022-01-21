<template>
  <div>
    <Header />
    <ImagesSectiont />
    <AboutUs />
    <ServicesSection />
    <FormSection />
    <Footer />
  </div>
</template>
<script>
import Header from "../components/Header";
import ImagesSectiont from "../components/ImagesSectiont.vue";
import AboutUs from "../components/AboutUs";
import ServicesSection from "../components/ServicesSection.vue";
import FormSection from "../components/FormSection.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Home",
  components: {
    Header,
    ImagesSectiont,
    AboutUs,
    ServicesSection,
    FormSection,
    Footer,
  },
};
</script>

<style >
</style>