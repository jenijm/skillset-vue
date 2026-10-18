<script setup>
const message = 'Hello from Vue!';
</script>

<template>
  <main class="page">
    <section class="card">
      <div class="vue-mark" aria-hidden="true">
        <span class="outer-v"></span>
        <span class="inner-v"></span>
      </div>

      <p class="label">MY FIRST VUE APP</p>
      <h1>{{ message }}</h1>
      <p class="description">
        This simple component is running successfully with Vue.js and Vite.
      </p>

      <span class="status">
        <i aria-hidden="true"></i>
        App is running
      </span>
    </section>
  </main>
</template>
