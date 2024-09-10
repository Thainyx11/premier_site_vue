<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import PrimaryButton from './components/PrimaryButton.vue'
import Footer from './components/Footer.vue'

</script>

<template>
  <Nav></Nav>
  <main class="p-8">

  </main>

  <h1 class="text-3xl font-bold underline text-red-500">
    Hello world!
  </h1>
  <PrimaryButton>Click !</PrimaryButton>
  <Footer />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
