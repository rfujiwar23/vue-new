<template>
  <h2>Hello, {{ name }}</h2>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: 'Stranger',
    },
  },
}
</script>

<style type="text/css">
h2[data-v-57163366] {
  font-size: 30px;
  font-weight: bold;
}
</style>
