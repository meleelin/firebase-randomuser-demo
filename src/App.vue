<template lang="pug">
h1.text-4xl.font-bold {{ title }}
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    const title = ref("Hello World!");
    return { title };
  },
};
</script>

<style>
</style>