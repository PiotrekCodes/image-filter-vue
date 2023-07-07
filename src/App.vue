<script setup lang="ts">

</script>

<template>
  <div class="font-['Quicksand'] max-w-xl bg-white p-8 shadow-2xl rounded absolute m-auto left-0 right-0 mt-32">
    <h1 class="text-center text-3xl text-indigo-700">Vue Filters</h1>
    <div class="text-center my-8 py-32 text-slate-700 italic rounded border-4 border-double border-slate-700/25">
      Drag and drop image.
    </div>
    <div class="my-8">
      <canvas width="448" height="448"></canvas>
      <div class="text-white text-xl mt-4">
        <div class="flex justify-center gap-4">
          <button type="button" class="bg-pink-600 py-4 w-full">Filter</button>
          <button type="button" class="bg-pink-600 py-4 w-full">Filter</button>
          <button type="button" class="bg-pink-600 py-4 w-full">Filter</button>
        </div>
        <a class="bg-indigo-700 py-4 block w-full mt-2 text-center">
          Download
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
