<script setup lang="ts">
import { ref } from 'vue'
defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <div class="bg-image text-3xl p-20 justify-between items- flex">
    <button class='border-green-100 border-solid border-2' btn-style>1</button>
    <button class='border-green-100 border-solid border-2' btn-style>2</button>
    <button class='border-green-100 border-solid border-2' btn-style>3</button>
    </div>
    <div>

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

<style scoped>
.bg-image{
  background-image: url('../../assets/images/bg-sidebar-mobile.svg');
  background-repeat: no-repeat;
  background-size: center;
}
.btn-style{
  width:24px;
  height:24px;
  border-radius:50%;
}
.read-the-docs {
  color: #888;
}
</style>
