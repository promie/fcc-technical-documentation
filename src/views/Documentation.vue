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
  background-color: #eee;
  padding-top: 10px;
  border-radius: 5px;
  white-space: pre-wrap;
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
}
</style>
