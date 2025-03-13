<template>
  <NavbarComponents/>
  <RouterView/>
</template>

<script>
import NavbarComponents from '@/components/NavbarComponts.vue';

export default {
  components: {
    NavbarComponents,
  },
};
</script>
