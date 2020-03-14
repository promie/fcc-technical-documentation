<script>
import Content from '@/components/Content.vue'
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'Documentation',
  components: {
    Content,
    Navigation
  }
}
</script>

<template>
  <div class="documentation">
    <div class="navigation">
      <Navigation />
    </div>

    <div class="content">
      <Content />
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Alegreya+Sans+SC&display=swap');
@import url('https://fonts.googleapis.com/css?family=PT+Sans+Narrow&display=swap');
/* Mobile First Approach */
* {
  margin: 0;
}

.documentation {
  display: flex;
  flex-direction: column;
}

.navigation {
  flex: 5;
}

.content {
  flex: 1;
}

pre {
  background-color: #f1d43b;
  padding-top: 15px;
  border-radius: 5px;
  white-space: pre-wrap;
  font-weight: bold;
  font-family: 'PT Sans Narrow', sans-serif;
}

p {
  font-size: 16px;
  padding: 10px;
  font-family: 'PT Sans Narrow', sans-serif;
}

ul {
  font-family: 'PT Sans Narrow', sans-serif;
}

h2 {
  font-family: 'Alegreya Sans SC', sans-serif;
  font-weight: bold;
  font-size: 28px;
}

@media only screen and (max-width: 600px) {
  .navigation {
    border-bottom: 1px solid grey;
  }
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .documentation {
    flex-direction: row;
    width: 100%;
  }

  .content {
    flex: 5;
    overflow-x: auto;
  }

  .navigation {
    flex: 1;
    overflow-x: auto;
    border-right: 2px solid grey;
  }

  p {
    font-size: 16px;
  }
}
</style>
