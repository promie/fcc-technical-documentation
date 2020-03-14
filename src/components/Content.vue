<script>
import Introduction from '@/components/contents/Introduction.vue'
import Knowledge from '@/components/contents/Knowledge.vue'
import Javascript from '@/components/contents/Javascript.vue'
import HelloWorld from '@/components/contents/HelloWorld.vue'
import Variables from '@/components/contents/Variables.vue'
import DeclaringVariables from '@/components/contents/DeclaringVariables.vue'
import VariableScope from '@/components/contents/VariableScope.vue'
import GlobalVariables from '@/components/contents/GlobalVariables.vue'
import Constants from '@/components/contents/Constants.vue'
import DataTypes from '@/components/contents/DataTypes.vue'
import Conditional from '@/components/contents/Conditional.vue'
import While from '@/components/contents/While.vue'
import Functions from '@/components/contents/Functions.vue'
import Reference from '@/components/contents/Reference.vue'

export default {
  name: 'Content',
  components: {
    Introduction,
    Knowledge,
    Javascript,
    HelloWorld,
    Variables,
    DeclaringVariables,
    VariableScope,
    GlobalVariables,
    Constants,
    DataTypes,
    Conditional,
    While,
    Functions,
    Reference
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

    <div id="variables">
      <Variables />
    </div>

    <div id="declaringvariables">
      <DeclaringVariables />
    </div>

    <div id="variablescope">
      <VariableScope />
    </div>

    <div id="globalvariables">
      <GlobalVariables />
    </div>

    <div id="constants">
      <Constants />
    </div>

    <div id="datatypes">
      <DataTypes />
    </div>

    <div id="conditional">
      <Conditional />
    </div>

    <div id="while">
      <While />
    </div>

    <div id="functions">
      <Functions />
    </div>

    <div id="reference">
      <Reference />
    </div>
  </div>
</template>

<style scoped>
/* Mobile First Approach */
.content {
  padding: 30px 10px;
  overflow-x: auto;
  height: 95vh;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .content {
    padding: 20px;
  }
}
</style>
