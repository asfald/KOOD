<template>
  <div class="max-w-screen-2xl m-auto flex flex-col justify-center gap-y-12">
    <NavBar />
    <PhotoGallery />
    <WorkGallery />
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
import WorkGallery from "../components/WorkGallery.vue";
import PhotoGallery from "../components/PhotoGallery.vue";

export default defineComponent({
  name: "GalleryView",
  components: { NavBar, Footer, WorkGallery, PhotoGallery },

  setup() {
    return {};
  },
});
</script>