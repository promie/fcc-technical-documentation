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
    <div class="title">JS Documentation</div>
    <ul>
      <li
        v-for="(info, index) in information"
        v-bind:key="index"
      >
        <a v-bind:href="info.link">{{ info.description }}</a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
/* Mobile First Approach */

.title {
  padding: 10px 0 10px 10px;
  font-size: 30px;
  font-weight: bold;
  text-align: center;
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
