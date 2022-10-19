<script setup lang="ts">
import Test from './Test.vue'
</script>

<template>
  <div>
    <!-- The code below will work fine if we just use `v-slot` -->
    <Test>
      <template v-slot:default="{ user = { name: 'aaa' } }">
        {{ user.name }}
      </template>
    </Test>
    <!-- <Test>
      <template v-slot="{ user = { name: 'aaa' } }">
        {{ user.name }}
      </template>
    </Test> -->
  </div>
</template>
