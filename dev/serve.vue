<script>
import Vue from 'vue';
import VueElementHighlight from '@/vue-element-highlight.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueElementHighlight
  }
});
</script>

<template>
  <div id="app">
    <vue-element-highlight :is-active="true">
      <span>Feature</span>
    </vue-element-highlight>
  </div>
</template>
