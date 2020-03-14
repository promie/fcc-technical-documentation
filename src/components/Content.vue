<script>
import Introduction from '@/components/contents/Introduction.vue'

export default {
  name: 'Content',
  components: {
    Introduction
  }
}
</script>

<template>
  <div class="content">
    <div id="introduction">
      <Introduction />
    </div>
  </div>
</template>

<style scoped>
/* Mobile First Approach */
.content {
  padding: 30px 10px;
  overflow-x: auto;
  border: solid 1px red;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .content {
    padding: 20px;
  }
}
</style>
