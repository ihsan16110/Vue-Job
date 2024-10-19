<script setup>
 import Navbar from '@/components/Navbar.vue';
 import { RouterView } from 'vue-router';
</script>


<template>
   <Navbar/>
   <RouterView/>
   <!-- <Hero/>
   <HomeCards/>
   <JobListings :limit="6" :showButton ="true"/> -->
</template>


