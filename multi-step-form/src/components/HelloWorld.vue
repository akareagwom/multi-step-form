<template>
<div class='bg-white w-[85%] absolute top-[15%] left-[5%] shadow p-4 rounded-[10px] flex flex-col items-center'>
    <h1 class="text-3xl text-left text-black">king</h1>
    
</div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true,
    },
  },
});
</script>


