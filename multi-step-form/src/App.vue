<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import StepOne from './components/StepOne.vue';
</script>

<template class="bg-[hsl(213, 96%, 18%)] w-[100%] bg-[red] h-[100vh]">
  <img src="" alt="" srcset="">
  <div class="hsl(228, 100%, 84%) bg-teal-50 h-[100vh]">
    <!-- <HelloWorld msg="" class="w-full main" /> -->
     <div class="p-4">
       <StepOne msg="" class="w-full main" />
     </div>
    <Footer></Footer>
  </div>
</template>

<style scoped>
.main{
  padding-left:0;
}
</style>

