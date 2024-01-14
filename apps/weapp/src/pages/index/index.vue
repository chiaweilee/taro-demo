<script setup>
import { ref } from 'vue'

const msg = ref('Hello world')
</script>

<template>
  <view>
    <text>{{ msg }}</text>
  </view>
</template>
