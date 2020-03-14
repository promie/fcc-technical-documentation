<script>
import { LINKS } from '@/constants'

export default {
  name: 'Navigation',
  created() {
    this.information = LINKS
  }
}
</script>

<template>
  <div class="navigation">
    <div class="title">JS DOCUMENTATION</div>
    <ul>
      <a
        v-for="(info, index) in information"
        v-bind:key="index"
        v-bind:href="info.link"
        ><li>{{ info.description }}</li></a
      >
    </ul>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Alegreya+Sans+SC&display=swap');

/* Mobile First Approach */
.title {
  padding: 10px 0 10px 10px;
  font-size: 30px;
  font-weight: bold;
  text-align: center;
  font-family: 'Alegreya Sans SC', sans-serif;
  background-color: #f1d43b;
  color: #000;
}

ul {
  list-style-type: none;
  padding: 0;
  overflow-x: auto;
  height: 200px;
}

li {
  border-top: solid 1px grey;
  padding: 10px;
}

a {
  text-decoration: none;
  color: black;
  font-size: 16px;
  cursor: pointer;
  font-family: 'Alegreya Sans SC', sans-serif;
}

li:hover,
a:hover {
  background-color: #f1d43b;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */

  .title {
    padding: 10px 0 10px 15px;
  }

  ul {
    height: 94vh;
  }

  li {
    padding: 15px;
  }

  a {
    font-size: 18px;
  }
}
</style>
