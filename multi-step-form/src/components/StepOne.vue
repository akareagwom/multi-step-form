<template>
<div class='bg-white w-[90%] absolute top-[15%] left-[5%] shadow rounded-[10px]'>
    <h1>Personal info</h1>
    <p>Please provide your name, email address, and phone number</p>
    <form class="flex flex-col">
        <label>Name</label>
        <input type="text" v-model="name" placeholder="Enter your name" class=""/>
        <label>Email Address</label>
        <input type="text" v-model="name" placeholder="Enter your name" class=""/>
        <label>Phone Number</label>
        <input type="text" v-model="name" placeholder="Enter your name" class=""/>
    </form>
</div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StepOne',
  props: {
    msg: {
      type: String,
      required: true,
    },
  },
});
</script>