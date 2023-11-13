<script setup lang="ts">

import VClicks from '@slidev/client/builtin/VClicks.ts'

</script>

<style>
.stack {
  position: relative;
}

.stack > *{
  position: absolute;
  top: 0;
  left: 0;
}
</style>

<template>
  <div class="stack">
    <VClicks>
      <slot></slot>
    </VClicks>
  </div>
</template>
