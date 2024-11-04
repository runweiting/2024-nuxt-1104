<template>
  <main class="container">
    <div class="rounded-3xl bg-black m-8 p-20 h-auto">
      <p class="text-9xl font-bold font-elf text-white pt-12">Page: ㄓㄜˋㄕˋㄕㄡˇㄧㄝˋ</p>
      <p class="text-6xl font-elf text-gray-400 pt-12">ㄇㄨˋㄑㄧㄢˊㄌㄨˋㄧㄡˊㄉㄜ˙ㄌㄨˋㄐㄧㄥˋㄨㄟˊ route.fullPath: {{ route.fullPath }}</p>
    </div>
  </main>
</template>

<script setup lang="ts">
const route = useRoute()
</script>
