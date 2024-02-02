<script setup>
export default {
  props: {
    msg: String,
  },
  data() {
    return {test: "test"}
  }
}
</script>

<template>
  <div>
    {{msg}}
  </div>
</template>

<style scoped>

</style>