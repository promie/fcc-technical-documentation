<script>
export default {
  name: 'GlobalVariables'
}
</script>

<template>
  <div>
    <div class="title">Global variables</div>
    <div class="description">
      <p>
        Global variables are in fact properties of the global object. In web
        pages the global object is window, so you can set and access global
        variables using the window.variable syntax.
      </p>
      <p>
        Consequently, you can access global variables declared in one window or
        frame from another window or frame by specifying the window or frame
        name. For example, if a variable called phoneNumber is declared in a
        document, you can refer to this variable from an iframe as
        parent.phoneNumber.
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
