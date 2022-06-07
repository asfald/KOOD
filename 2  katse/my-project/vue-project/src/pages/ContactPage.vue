<template>
  <div class="max-w-screen-2xl m-auto flex flex-col justify-center gap-y-12">
    <NavBar />
    <ContactForm />
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
import ContactForm from "../components/ContactForm.vue";

export default defineComponent({
  name: "ContactPage",
  components: { NavBar, Footer, ContactForm },
  setup() {
    return {};
  },
});
</script>