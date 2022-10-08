<!-- Please remove this file from your project -->
<template>
  <div
    class="menu flex justify-around h-10 bg-gray-100 items-center sm:text-xl"
  >
    <nuxt-link to="/#">Home</nuxt-link>
    <nuxt-link to="/sobre">Sobre</nuxt-link>
    <nuxt-link to="/fac">Fale conosco</nuxt-link>
  </div>
</template>

<script>
export default {
  name: "MenuComponent",
};
</script>
<style>
.menu .nuxt-link-active {
  color: #38aa6c;
  border-bottom: 1.5px solid #38aa6c;
}
</style>
