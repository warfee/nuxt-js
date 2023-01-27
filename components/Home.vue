<!-- Please remove this file from your project -->
<template>
  <div class="card" style="margin: 2em 2em 2em 2em;">
      <div class="card-inner">
          <h5 class="card-title">Warfee Nuxt Test</h5>
          <!-- <h6 class="card-subtitle mb-2">Test .. .. .. </h6> -->
          <p class="card-text">Menus :</p>
          <a href="#" class="card-link"><NuxtLink to="/auth/login">Login</NuxtLink></a>
          
          <a href="#" class="card-link"><NuxtLink to="/auth/forgot-pass">Forgot Password</NuxtLink></a>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>
