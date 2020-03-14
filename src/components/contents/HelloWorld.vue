<script>
export default {
  name: 'HelloWorld'
}
</script>

<template>
  <div>
    <div class="title">Hello World</div>
    <div class="description">
      <p>
        To get started with writing JavaScript, open the Scratchpad and write your first "Hello world" JavaScript code:
      </p>

      <pre>
        function greetMe(yourName) { alert("Hello " + yourName); }
        greetMe("World");
      </pre>
      <p>
        Select the code in the pad and hit Ctrl+R to watch it unfold in your browser!
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

pre {
  background-color: #eee;
  padding-top: 10px;
  border-radius: 3px;
  width: 100%;
  font-size: 9px;
  white-space: pre-wrap;
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

  pre {
    font-size: 14px;
  }
}
</style>
