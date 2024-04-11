<template>
  <div class="hero min-h-screen bg-base-200">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <div class="indicator w-full max-w-md md:ml-8">
        <span class="indicator-item badge badge-accent">{{ count }}</span>
        <div class="mockup-code w-full">
          <pre data-prefix="$"><code>npm i pancakes</code></pre>
        </div>
      </div>
      <div class="max-w-2xl text-center md:text-left">
        <h1 class="text-5xl font-bold">Young Men's Society :3</h1>
        <p class="py-6">
          The Young Men's Society is dedicated to helping young men to shape
          their destiny, embrace their potential, and build a brighter future
          together.
        </p>
        <button class="btn btn-primary" @click="count++">Join Us</button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const count = ref(40);
</script>
