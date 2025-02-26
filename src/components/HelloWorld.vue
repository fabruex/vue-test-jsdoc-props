<script setup lang="ts">
  defineProps<{
    /**
     * Single word prop
     */
    singlewordprop: string
    /**
     * Two words prop
     */
    twowordsProp: string
    /**
     * Three words prop
     */
    threeWordsProp: string

  }>()
</script>

<template>
  <div>{{ singlewordprop }}</div>
  <div>{{ twowordsProp }}</div>
  <div>{{ threeWordsProp }}</div>
</template>

<style scoped>

</style>
