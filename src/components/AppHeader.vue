<script>
export default {
  name: 'Header',
  data() {
    return {};
  },
};
</script>

<template>
  <header class="row mx-0 py-2">
    <div
      class="custom-container col-10 col-sm-11 d-flex justify-content-between px-0 align-items-center"
    >
      <!-- logo small -->
      <div class="sx d-sm-none">
        <a href="" class="cont-img">
          <img src="../../public/img/logo/logo-small.png" alt="logo" />
        </a>
      </div>

      <!-- logo big -->
      <div class="sx d-none d-sm-block">
        <a href="" class="cont-img">
          <img src="../../public/img/logo/logo-big.png" alt="logo" />
        </a>
      </div>

      <div class="dx d-flex align-items-center">
        <a href="" class="custom-btn text-uppercase me-5 d-none d-md-block"
          >get in touch</a
        >
        <a href="" class="custom-btn text-uppercase">menu</a>
      </div>
    </div>
  </header>
</template>

<style scoped lang="scss">
@use '../assets/scss/style.scss' as *;

header {
  background-color: #303132;
}

.custom-container {
  margin: 0 auto;
  color: #f5f5f5;

  .sx {
    .cont-img {
      height: 100px;

      img {
      }
    }
  }

  .dx {
  }
}
</style>
