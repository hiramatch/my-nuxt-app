<template>
  <div>
    <h2 class="green">
      This is Demo Page
    </h2>
    <p>Hello {{ name }}</p>
  </div>
</template>

<script>
export default {
  layout: 'custom_layout',
  asyncData (context) {
    return { name: 'World' }
  }
}
</script>
<style>
  .green {
    color: green;
  }
</style>
