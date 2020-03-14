<script>
export default {
  name: 'Navigation'
}
</script>

<template>
  <div class="navigation">
    <div class="title">JS Documentation</div>
    <ul>
      <li>Introduction</li>
      <li>What you should already know</li>
      <li>JavaScript and Java</li>
      <li>Hello world</li>
      <li>Variables</li>
      <li>Declaring variables</li>
      <li>Variable scope</li>
      <li>Global Variables</li>
      <li>Constants</li>
      <li>Data types</li>
      <li>if...else statement</li>
      <li>while statement</li>
      <li>Function declarations</li>
      <li>Reference</li>
    </ul>
  </div>
</template>

<style scoped>
/* Mobile First Approach */

.title {
  font-size: 25px;
}

ul {
  list-style-type: none;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .navigation {
    min-height: 100vh;
  }
}
</style>
