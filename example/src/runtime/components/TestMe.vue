<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    count: {
      type: Number,
      required: true,
    },
  },
})
</script>

<template>
  <div>
    {{ count }}
  </div>
</template>
