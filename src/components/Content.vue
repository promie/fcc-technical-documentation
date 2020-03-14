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
    <div id="introduction" class="section">
      <Introduction />
    </div>
    <div id="knowledge" class="section">
      <Knowledge />
    </div>

    <div id="javascript" class="section">
      <Javascript />
    </div>

    <div id="helloworld" class="section">
      <HelloWorld />
    </div>

    <div id="variables" class="section">
      <Variables />
    </div>

    <div id="declaringvariables" class="section">
      <DeclaringVariables />
    </div>

    <div id="variablescope" class="section">
      <VariableScope />
    </div>

    <div id="globalvariables" class="section">
      <GlobalVariables />
    </div>

    <div id="constants" class="section">
      <Constants />
    </div>

    <div id="datatypes" class="section">
      <DataTypes />
    </div>

    <div id="conditional" class="section">
      <Conditional />
    </div>

    <div id="while" class="section">
      <While />
    </div>

    <div id="functions" class="section">
      <Functions />
    </div>

    <div id="reference" class="section">
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

.section {
  margin-bottom: 20px;
}

@media only screen and (min-width: 768px) {
  /* Desktop View */
  .content {
    padding: 20px;
  }
}
</style>
