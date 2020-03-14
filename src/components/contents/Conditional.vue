<script>
export default {
  name: 'Conditional'
}
</script>

<template>
  <div>
    <h2>if...else statement</h2>
    <div class="description">
      <p>
        Use the if statement to execute a statement if a logical condition is
        true. Use the optional else clause to execute a statement if the
        condition is false. An if statement looks as follows:
      </p>
      <pre>
        if (condition) { statement_1; } else { statement_2; }
      </pre>
      <p>
        condition can be any expression that evaluates to true or false. See
        Boolean for an explanation of what evaluates to true and false. If
        condition evaluates to true, statement_1 is executed; otherwise,
        statement_2 is executed. statement_1 and statement_2 can be any
        statement, including further nested if statements.
      </p>
      <p>
        You may also compound the statements using else if to have multiple
        conditions tested in sequence, as follows:
      </p>
      <pre>
        if (condition_1) { statement_1; } else if (condition_2) { statement_2;
        } else if (condition_n) { statement_n; } else { statement_last; }
      </pre>
      <p>
        In the case of multiple conditions only the first logical condition
        which evaluates to true will be executed. To execute multiple
        statements, group them within a block statement ({ ... }) . In general,
        it's good practice to always use block statements, especially when
        nesting if statements:
      </p>
      <pre>
        if (condition) { statement_1_runs_if_condition_is_true;
        statement_2_runs_if_condition_is_true; } else {
        statement_3_runs_if_condition_is_false;
        statement_4_runs_if_condition_is_false; }
      </pre>
      <p>
        It is advisable to not use simple assignments in a conditional
        expression, because the assignment can be confused with equality when
        glancing over the code. For example, do not use the following code:
      </p>
      <pre>
        if (x = y) { /* statements here */ }
      </pre>
      <p>
        If you need to use an assignment in a conditional expression, a common
        practice is to put additional parentheses around the assignment. For
        example:
      </p>
      <pre>
        if ((x = y)) { /* statements here */ }
      </pre>
    </div>
  </div>
</template>
