<script>
export default {
  name: 'Knowledge'
}
</script>

<template>
  <div>
    <h2>What you should already know</h2>
    <div class="description">
      <p>
        This guide assumes you have the following basic background:
      </p>
      <ul>
        <li>
          A general understanding of the Internet and the World Wide Web (WWW).
        </li>
        <li>
          Good working knowledge of HyperText Markup Language (HTML).
        </li>
        <li>
          Some programming experience. If you are new to programming, try one of
          the tutorials linked on the main page about JavaScript.
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
/* Mobile First Approach */
li {
  padding: 5px;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  li {
    padding: 10px;
  }
}
</style>
