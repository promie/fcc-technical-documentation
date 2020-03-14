<script>
export default {
  name: 'Navigation'
}
</script>

<template>
  <div class="navigation">
    <div class="title">JS Documentation</div>
    <ul>
      <li><a href="#">Introduction</a></li>
      <li><a href="#">What you should already know</a></li>
      <li><a href="#">JavaScript and Java</a></li>
      <li><a href="#">Hello world</a></li>
      <li><a href="#">Variables</a></li>
      <li><a href="#">Declaring variables</a></li>
      <li><a href="#">Variable scope</a></li>
      <li><a href="#">Global Variables</a></li>
      <li><a href="#">Constants</a></li>
      <li><a href="#">Data types</a></li>
      <li><a href="#">if...else statement</a></li>
      <li><a href="#">while statement</a></li>
      <li><a href="#">Function declarations</a></li>
      <li><a href="#">Reference</a></li>
    </ul>
  </div>
</template>

<style scoped>
/* Mobile First Approach */

.title {
  padding: 10px 0 10px 10px;
  font-size: 30px;
  font-weight: bold;
}

ul {
  list-style-type: none;
  padding: 0;
  overflow-x: auto;
  height: 200px;
}

li {
  border-top: solid 1px grey;
  padding: 10px;
}

a {
  text-decoration: none;
  color: black;
  font-size: 18px;
  cursor: pointer;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */

  .title {
    padding: 10px 0 10px 15px;
  }

  ul {
    height: 94vh;
  }

  li {
    padding: 15px;
  }

  a {
    font-size: 18px;
  }
}
</style>
