<script>
export default {
  name: 'Knowledge'
}
</script>

<template>
  <div>
    <div class="title">What you should already know</div>
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
.title {
  font-weight: bold;
  font-size: 18px;
}

p {
  font-size: 16px;
  padding: 10px;
}

li {
  padding: 5px;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .title {
    font-weight: bold;
    font-size: 20px;
  }

  p {
    font-size: 16px;
  }

  li {
    padding: 10px;
  }
}
</style>
