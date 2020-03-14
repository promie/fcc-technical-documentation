<script>
export default {
  name: 'Reference'
}
</script>

<template>
  <div>
    <div class="title">Reference</div>
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
