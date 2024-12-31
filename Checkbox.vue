<script setup lang="ts">
import { Checkbox } from './foo'

defineProps<{
  foo: string
}>()
</script>

<template>
  <Checkbox bar="hello" />
</template>
