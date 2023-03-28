<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings ">
    <h1 class="text-3xl font-bold underline line-through">medicare </h1>
    <h4> Lets do medical stuffs</h4>
    <p> Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolor est totam cum quibusdam. Eveniet corrupti, assumenda aliquam itaque, incidunt suscipit debitis aut sint, voluptatem sit cupiditate totam! Natus, earum quasi.</p>
  </div>
  <div>

  </div>
</template>

<style scoped>

h1{
  font-family: 'RedHatDisplay-Bold';
}

h3 {
  font-size: 1.2rem;
  font-family: 'RedHatDisplay-Bold';
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
