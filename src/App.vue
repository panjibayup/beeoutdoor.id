<template>
  <div id="app">
    <router-view />
    <FooterPage />
  </div>
</template>

<script>
import FooterPage from "./components/FooterPage.vue";

export default {
  components: { FooterPage },
};
</script>
