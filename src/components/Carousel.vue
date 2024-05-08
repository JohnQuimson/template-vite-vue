<script>
export default {
  name: 'Carousel',
  data() {
    return {
      technologies: ['bootstrap.png', 'css.png', 'html.png'],
    };
  },
};
</script>

<template>
  <section>
    <img src="../../public/icons/javascript.png" alt="img" />
  </section>
</template>

<style scoped lang="scss">
@use '../assets/scss/style.scss' as *;
</style>
