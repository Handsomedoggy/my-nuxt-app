<template>
  <div
    class="
      relative
      flex flex-col
      items-top
      justify-center
      min-h-screen
      bg-gray-100
      sm:items-center
      sm:pt-0
    "
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <nuxt-logo />
    <br />
    <h1>Cloudbase is awesome!</h1>
  </div>
</template>

<script>
import NuxtLogo from '../components/NuxtLogo.vue'
export default {
  components: { NuxtLogo },
}
</script>
<style scoped>
.body {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
</style>
