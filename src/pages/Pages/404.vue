<template>
  <div class="not-found-page">
    <div class="centered">
      <h1><i class="not-found-icon nc-icon nc-puzzle-10"></i>404</h1>
      <p>The page you requested could not be found.</p>
      <p><router-link to="/" class="btn">Back to Home</router-link></p>
    </div>
  </div>
</template>

<script>
//import AuthLayout from 'src/pages/Pages/AuthLayout.vue';

export default {
    components: {
       // AuthLayout
    }
};
</script>
<style lang="scss">
  .not-found-page {
    .full-page > .content,
    .centered {
      min-height: calc(100vh - 160px);
    }
    .not-found-icon {
      margin-right: 10px;
    }
    .centered {
      h1,
      i {
        font-size: 50px;
      }
      p {
        font-size: 20px;
      }
      display: flex;
      padding-bottom: 150px;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      color: white;
    }
  }
</style>
