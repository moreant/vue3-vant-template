<script setup lang="ts">
  import { Button } from 'vant'
  import { useRouter } from 'vue-router'

  const router = useRouter()

  const toHome = () => {
    router.push({ path: '/' })
  }
</script>

<template>
  <h1>About</h1>
  <Button plain type="primary" @click="toHome">Back Home</Button>
</template>

<style></style>
