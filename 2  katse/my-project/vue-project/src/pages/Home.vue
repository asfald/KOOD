<template>
  <div
    class="
      flex flex-col
      lg:gap-y-24
      gap-y-12
      justify-center
      align-center
      max-w-screen-xl
      m-auto
      font-roboto
    "
  >
    <NavBar />

    <div class="flex justify-center">
      <iframe
        class="aspect-video w-full m-auto lg:px-12"
        src="https://www.youtube.com/embed/wp43OdtAAkM?rel=0&modestbranding=1&autohide=1&mute=0&showinfo=0&controls=1&autoplay=0"
        frameborder="0"
        allow="autoplay"
        allowfullscreen
      ></iframe>
    </div>
    <div
      class="
        flex flex-col
        lg:flex-row
        justify-center
        space-x-0
        lg:space-x-16
        m-auto
        lg:px-12
      "
    >
      <div>
        <img
          class="lg:max-w-2xl md:max-w-xl max-w-xs h-auto m-auto"
          src="./../assets/img/ruut.jpg"
          alt=""
        />
      </div>
      <div class="flex flex-col justify-center text-center lg:text-left">
        <h1
          class="
            uppercase
            text-2xl
            lg:text-3xl
            tracking-wider
            font-bold
            pt-12
            md:pt-0
          "
        >
          rain oselin
        </h1>
        <p
          class="
            uppercase
            m-auto
            text-sm
            lg:text-xl
            py-6
            md:leading-6
            w-80
            md:w-96
            lg:w-full
          "
        >
          Olen front-end arendaja ning multimeediatudeng tallinna
          polütehnikumis. See siin on minu portfoolio.
        </p>
        <p class="uppercase text-sm lg:text-2xl pb-6">
          mõned asjad, <br />millega olen tuttav:
        </p>

        <div
          class="flex flex-wrap w-40 m-auto md:w-full lg:w-full justify-center"
        >
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/yks.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/kaks.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/kolm.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/neli.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/viis.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/kuus.svg"
            alt="logo"
          />
          <img
            class="lg:w-12 md:w-10 w-6 h-auto"
            src="./../assets/svg/viisteist.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/kaheksa.svg"
            alt="logo"
          />
          <img
            class="lg:w-12 md:w-8 w-6 h-auto"
            src="./../assets/svg/seitse.svg"
            alt="logo"
          />
          <img
            class="lg:w-12 md:w-10 w-6 h-auto"
            src="./../assets/svg/kymme.svg"
            alt="logo"
          />
          <img
            class="lg:w-12 md:w-10 w-6 h-auto"
            src="./../assets/svg/yksteist.svg"
            alt="logo"
          />
          <img
            class="lg:w-12 md:w-8 w-6 h-auto"
            src="./../assets/svg/kaksteist.svg"
            alt="logo"
          />
          <img
            class="lg:w-16 md:w-12 w-8 h-auto"
            src="./../assets/svg/neliteist.svg"
            alt="logo"
          />
        </div>
      </div>
    </div>
    <HomeGallery />
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { RouterLink, RouterView } from "vue-router";
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
import HomeGallery from "../components/HomeGallery.vue";

export default defineComponent({
  name: "Home",
  components: {
    NavBar,
    Footer,
    HomeGallery,
  },
  props: {},

  setup() {
    return {};
  },
});
</script>
