<template>
  <div class="recognize">
    <BciWave />
    <ValidPeople />
  </div>
</template>

<script lang="ts" setup>
// @ is an alias to /src

import BciWave from "@/components/BciWave.vue";
import ValidPeople from "@/components/ValidPeople.vue";
</script>

<style scoped>
.recognize {
  margin-top: 50px;
  display: flex;
  flex: auto;
}
</style>
