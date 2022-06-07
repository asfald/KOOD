<template>
<div class="max-w-screen-2xl m-auto flex justify-center">
  <NavBar/>

</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { RouterLink, RouterView } from "vue-router";
import NavBar from './NavBar.vue'

export default defineComponent({
  name: "ContactForm",
  components: {NavBar},
  setup() {
    return {};
  },
});
</script>