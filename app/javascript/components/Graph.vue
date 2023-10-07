<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
  <p>Real {{ count }}</p>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
