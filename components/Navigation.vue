<template>
  <div>
    <nav class="navigation">
      <Logo />
      <nuxt-link to="/">Main</nuxt-link>
      <nuxt-link to="/about">About page</nuxt-link>
      <nuxt-link to="/id">Id page</nuxt-link>
      <nuxt-link to="/id/123">ID 123</nuxt-link>
    </nav>
  </div>
</template>

<script>
  import Logo from '@/components/navigation/Logo.vue'
  export default {
    components: {
      Logo
    }

  }
</script>

<style scoped>
.navigation {
  width: 100%;
  height: 80px;
  padding: 20px;
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: lightblue;
}
</style>
