    <template>
    <div class='bg-white justify-center shadow p-4 rounded-[10px] flex flex-col items-center'>
        <h1 class="text-3xl text-left text-black">Personal info</h1>
        <p class="text-left p-4">Please provide your name, email address, and phone number</p>
        <form class="flex flex-col">
            <label>Name</label>
            <input type="text" placeholder="e.g.Stephen King" class="px-12 py-4 border-2 border-[hsl(213, 96%, 18%)] rounded-[5px] border-solid"/>
            <label>Email Address</label>
            <input type="text" placeholder="e.g.stephenking@lorem.com" class="px-12 py-4 border-2 border-[hsl(213, 96%, 18%)] rounded-[5px] border-solid"/>
            <label>Phone Number</label>
            <input type="text" placeholder="e.g.+1 234 567 890" class="px-12 py-4 border-2 border-[hsl(213, 96%, 18%)] rounded-[5px] border-solid"/>
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