<script>
export default {
  name: 'DeclaringVariables'
}
</script>

<template>
  <div>
    <div class="title">Declaring variables</div>
    <div class="description">
      <p>
        You can declare a variable in three ways:
      </p>
      <p>
        With the keyword var. For example,
      </p>
      <pre>
        var x = 42.
      </pre>
      <p>
        This syntax can be used to declare both local and global variables.
      </p>
      <p>
        By simply assigning it a value. For example,
      </p>
      <pre>
        x = 42.
      </pre>
      <p>
        This always declares a global variable. It generates a strict JavaScript warning. You shouldn't use this variant.
      </p>
      <p>
        With the keyword let. For example,
      </p>
      <pre>
        let y = 13.
      </pre>
      <p>
        This syntax can be used to declare a block scope local variable. See Variable scope below.
      </p>
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

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .title {
    font-weight: bold;
    font-size: 20px;
  }

  p {
    font-size: 16px;
  }
}
</style>
