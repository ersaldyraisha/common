<template>
  <button
    class="btn"
    @click="$emit('click')"
  >
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: 'Button'
}
</script>

<style scoped>
  .btn {
    background: red;
  }
</style>