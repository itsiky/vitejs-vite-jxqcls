<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <!--h1>{{ msg }}</h1-->
  <h1>Welcome</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
    <!--code>components/HelloWorld.vue</code-->
      
      my new site of itsik yehuda 
  </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Made by itsik yehuda.</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
