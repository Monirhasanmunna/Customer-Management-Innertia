<script setup>
    import Navbar from './Navbar.vue';
    import Sidebar from './Sidebar.vue'
</script>

<template>

<Navbar/>

<Sidebar/>


<div class="p-4 sm:ml-64">
   <div class="p-4 border-2 border-gray-200 border-dashed rounded-lg dark:border-gray-700 mt-14">
      <slot></slot>
      
   </div>
</div>
</template>

<style scoped>

</style>