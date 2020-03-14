<script>
export default {
  name: 'Constants'
}
</script>

<template>
  <div>
    <h2>Constants</h2>
    <div class="description">
      <p>
        You can create a read-only, named constant with the const keyword. The
        syntax of a constant identifier is the same as for a variable
        identifier: it must start with a letter, underscore or dollar sign and
        can contain alphabetic, numeric, or underscore characters.
      </p>
      <pre>
        const PI = 3.14;
      </pre>
      <p>
        A constant cannot change value through assignment or be re-declared
        while the script is running. It has to be initialized to a value.
      </p>
      <p>
        The scope rules for constants are the same as those for let block scope
        variables. If the const keyword is omitted, the identifier is assumed to
        represent a variable.
      </p>
      <p>
        You cannot declare a constant with the same name as a function or
        variable in the same scope. For example:
      </p>
      <pre>
        // THIS WILL CAUSE AN ERROR function f() {}; const f = 5; 
        // THIS WILL CAUSE AN ERROR ALSO function f() { const g = 5; var g; //statements
        }
      </pre>
      <p>
        However, object attributes are not protected, so the following statement
        is executed without problems.
      </p>
      <pre>
        const MY_OBJECT = {"key": "value"}; MY_OBJECT.key = "otherValue";
      </pre>
    </div>
  </div>
</template>
