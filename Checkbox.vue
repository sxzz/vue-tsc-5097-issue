<script setup lang="ts">
import { Checkbox } from './foo'
// import Checkbox from './foo/Checkbox.vue' // works well

defineProps<{
  foo: string
}>()
</script>

<template>
  <Checkbox bar="hello" />
</template>
