<script lang="ts" setup>
import { defineProps } from 'vue'

const props = defineProps<{
  count: number
}>()
</script>

<template>
  <div>
    {{ props.count }}
  </div>
</template>
