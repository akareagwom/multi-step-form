<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <div class="bg-image">
    <h1></h1>
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
  background-image: url('../../assets/images/bg-sidebar-desktop.svg');
}
.read-the-docs {
  color: #888;
}
</style>
