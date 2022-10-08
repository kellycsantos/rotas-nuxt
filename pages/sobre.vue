<template>
    <div class="text-xl flex  flex-col text-center">
        <Menu />
        <h1 class="text-3xl mt-6">Sobre a empresa</h1>
        <p class="mt-6 text-md">Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit similique dolor, itaque nemo voluptatem, laudantium, nisi quo ex fugiat dignissimos incidunt tenetur quasi.</p>
    </div>
   
  </template>
  
  <script>
import Menu from '~/components/Menu.vue';
  export default {
    name: "Empresa",
    components: { Menu }
}
  </script>
  