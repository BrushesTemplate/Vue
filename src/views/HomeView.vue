<template>
  <div class="home">
    <img
      alt="Vue logo"
      src="../assets/logo.png"
      style="width: 300px; height: 300px"
    />
    <HelloWorld msg="Welcome to QJ-Cli !" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>
