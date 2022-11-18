<template>
  <div>
    <Nuxt></Nuxt>
    <TheFooter />
  </div>
</template>

<script lang="ts">
  import '@nuxtjs/axios';
  import { defineComponent } from 'vue';
  import SideBar from '~/components/SideBar.vue';
  import TheFooter from '~/components/TheFooter.vue';

  export default defineComponent({
    components: {
      SideBar,
      TheFooter,
    },
    data() {
      return {};
    },
  });
</script>
