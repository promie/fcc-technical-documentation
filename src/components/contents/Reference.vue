<script>
export default {
  name: 'Reference'
}
</script>

<template>
  <div>
    <h2>Reference</h2>
    <div class="description">
      <ul>
        <li>
          All the documentation in this page is taken from
          <a
            href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide"
            target="_blank"
            >MDN</a
          >
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
