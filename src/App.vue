
<template>
  <div
    class="font-chicle flex flex-col justify-around mx-10 py-5 h-full"
    style="color: #fffdd0"
  >
    <h1 class="text-5xl -mb-6">Summer Blowout Richmond 2k22</h1>
    <div class="mb-6">
      <h2 class="text-3xl mb-2">@ 219 East Broad St</h2>
      <h2 class="text-2xl">Friday June 17 @ 6:30 pm</h2>
    </div>

    <div class="">
      <h3 class="text-xl italic">When you arrive...</h3>
      <p class="text-lg">
        Go in through the Grace St entrance and the door should be propped open.
        Walk to the center of the lobby and go up the elevator to the fifth
        floor. Go down the hallway to the roottop entrance.
      </p>
      <p class="text-lg my-5 mt-16">Text (917)-603-7681 if you have any issues.</p>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  data() {
    return {
      msg: "Hello Vue 3 + Vite",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
