<template>
  <div class="about">
    <div class="home-btn">
      <router-link :to="{ name: 'Home' }">Return to Home</router-link>
    </div>
    <h1>This is an InstBusiness page</h1>
  </div>
</template>

<script>
export default {
  name: 'InstBusiness',
}
</script>
