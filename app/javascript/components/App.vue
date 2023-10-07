<template>
  <div>
    <h1>App</h1>
    <Graph />
  </div>
</template>

<script>
import Graph from "~/components/Graph.vue";

export default {
  components: {Graph},
  data() {
    return {
      count: 0
    }
  }
}
</script>

<style lang="scss" scoped>

</style>
