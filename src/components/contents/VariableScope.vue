<script>
export default {
  name: 'Variable Scope'
}
</script>

<template>
  <div>
    <div class="title">Variable scope</div>
    <div class="description">
      <p>
        When you declare a variable outside of any function, it is called a
        global variable, because it is available to any other code in the
        current document. When you declare a variable within a function, it is
        called a local variable, because it is available only within that
        function.
      </p>
      <p>
        JavaScript before ECMAScript 2015 does not have block statement scope;
        rather, a variable declared within a block is local to the function (or
        global scope) that the block resides within. For example the following
        code will log 5, because the scope of x is the function (or global
        context) within which x is declared, not the block, which in this case
        is an if statement.
      </p>
      <pre>
        if (true) { var x = 5; } console.log(x); // 5
      </pre>
      <p>
        This behavior changes, when using the let declaration introduced in ECMAScript 2015.
      </p>
      <pre>
        if (true) { let y = 5; } console.log(y); // ReferenceError: y is not defined
      </pre>
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
