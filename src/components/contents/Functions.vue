<script>
export default {
  name: 'Functions'
}
</script>

<template>
  <div>
    <h2>Functions declarations</h2>
    <div class="description">
      <p>
        A function definition (also called a function declaration, or function
        statement) consists of the function keyword, followed by:
      </p>
      <ul>
        <li>The name of the function.</li>
        <li>
          A list of arguments to the function, enclosed in parentheses and
          separated by commas.
        </li>
        <li>
          The JavaScript statements that define the function, enclosed in curly
          brackets, { }.
        </li>
      </ul>
      <p>
        For example, the following code defines a simple function named square:
      </p>
      <pre>
        function square(number) { return number * number; }
      </pre>
      <p>
        The function square takes one argument, called number. The function
        consists of one statement that says to return the argument of the
        function (that is, number) multiplied by itself. The return statement
        specifies the value returned by the function.
      </p>
      <pre>
        return number * number;
      </pre>
      <p>
        Primitive parameters (such as a number) are passed to functions by
        value; the value is passed to the function, but if the function changes
        the value of the parameter, this change is not reflected globally or in
        the calling function.
      </p>
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
