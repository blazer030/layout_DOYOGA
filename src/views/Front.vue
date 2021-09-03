<template>
  <header-section></header-section>
  <main>
    <router-view />
  </main>
  <footer-section></footer-section>
</template>

<script>
import headerSection from '@/components/front/Header.vue';
import footerSection from '@/components/front/Footer.vue';

export default {
  components: {
    headerSection,
    footerSection,
  },
};
</script>
