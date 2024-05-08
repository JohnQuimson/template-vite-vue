<script>
import Jumbotron from './Jumbotron.vue';
import Slider from './Carousel.vue';

export default {
  name: 'Main',

  components: {
    Jumbotron,
    Slider,
  },
};
</script>

<template>
  <main>
    <Jumbotron />
    <Slider />
  </main>
</template>

<style lang="scss" scoped></style>
