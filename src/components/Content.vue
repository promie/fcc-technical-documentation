<script>
import Introduction from '@/components/contents/Introduction.vue'
import Knowledge from '@/components/contents/Knowledge.vue'
import Javascript from '@/components/contents/Javascript.vue'
import HelloWorld from '@/components/contents/HelloWorld.vue'

export default {
  name: 'Content',
  components: {
    Introduction,
    Knowledge,
    Javascript,
    HelloWorld
  }
}
</script>

<template>
  <div class="content">
    <div id="introduction">
      <Introduction />
    </div>
    <div id="knowledge">
      <Knowledge />
    </div>

    <div id="javascript">
      <Javascript />
    </div>

    <div id="helloworld">
      <HelloWorld />
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
