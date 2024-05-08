<script>
export default {
  name: 'Jumbotron',

  data() {
    return {};
  },
};
</script>

<template>
  <section class="jumbotron px-0">
    <div class="cont-text border border-danger text-uppercase">
      <h3 class="text-center">Hello! I'm</h3>
      <h1 class="m-0">
        John H.<br />
        Quimson
      </h1>
    </div>

    <div class="col-10 border d-flex justify-content-end pt-5">
      <h4 class="m-0">Jr Full Stack Web Developer</h4>
    </div>
  </section>
</template>

<style scoped lang="scss">
@use '../assets/scss/style.scss' as *;

.jumbotron {
  background-color: var(--custom-primary);
  border: 1px solid red;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  color: var(--custom-white);
  padding: clamp(50px, 10vw, 100px);

  h1 {
    font-size: clamp(70px, 10vw, 200px);
    line-height: clamp(70px, 10vw, 200px);
    font-weight: 800;
  }

  h3 {
    font-size: clamp(20px, 2vw, 40px);
    font-weight: 800;
  }

  h4 {
    font-size: clamp(20px, 2vw, 40px);
    font-weight: 800;
    margin-left: 100px;
  }
}

// /*
// ---------------------
// RESPONSIVE
// ---------------------
// */
// /* Extra Small da 0 a 576 */
// @media screen and (max-width: 576px) {
//   .jumbotron h1 {
//     color: red;
//     font-size: 80px;

//     line-height: 50px;
//   }
// }

// /* Small da 577 a 768 */
// @media screen and (min-width: 577px) and (max-width: 768px) {
//   .jumbotron h1 {
//     color: green;
//   }
// }

// /* Medium da 769 a 992 */
// @media screen and (min-width: 769px) and (max-width: 992px) {
//   .jumbotron h1 {
//     color: orange;
//   }
// }

// /* Large da 993 in poi */
// @media screen and (min-width: 993px) {
//   .jumbotron h1 {
//     color: yellow;
//   }
// }
//
</style>
