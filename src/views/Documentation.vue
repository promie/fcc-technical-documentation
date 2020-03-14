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
  border: 1px solid red;
}

.content {
  flex: 1;
  border: 1px solid red;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .documentation {
    flex-direction: row;
    width: 100%;
  }

  .content {
    flex: 5;
  }

  .navigation {
    flex: 1;
  }
}
</style>
