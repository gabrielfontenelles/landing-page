<template>
  <div>
    <HeaderSection />
    <BenefitsCarousel />
    <Testimonials />
    <ContactForm />
    <FooterCTA />
  </div>
</template>

<script>
import HeaderSection from "./components/HeaderSection.vue";
import BenefitsCarousel from "./components/BenefitsCarousel.vue";
import Testimonials from "./components/Testimonials.vue";
import ContactForm from "./components/ContactForm.vue";
import FooterCTA from "./components/FooterCTA.vue";

export default {
  components: {
    HeaderSection,
    BenefitsCarousel,
    Testimonials,
    ContactForm,
    FooterCTA,
  },
};
</script>
