<template>
    <div class="text-xl flex  flex-col text-center">
        <Menu />
        <h1 class="text-3xl mt-6">Fale conosco </h1>
        <div class="flex flex-col items-center px-2 mt-4">
        <input class="border-2 w-full sm:w-1/2 md:w-72 p-2"   type="email" v-model="empresa.email" readonly>
        <textarea class="border-2 w-full sm:w-1/2 md:w-72 p-2 my-6" ></textarea>
        <input class="bg-gray-100 cursor-pointer py-2 px-6 rounded-lg" type="submit">
      </div>
        
    </div>
   
  </template>
  
  <script>
import Menu from '~/components/Menu.vue';
  export default {
    name: "FacPage",
    components: { Menu },
    computed:{
      empresa(){
        let contato = {nome:'Nuxpress', email: 'nuxpress@jmail.com.br', tel:'(11)2211-9878'}
        return contato
      }
    }

}
  </script>
  <style>



</style>