<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { Vue2LibSampleSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  Vue2LibSampleSample,
  // }
});
</script>

<template>
  <div id="app">
    <vue2-lib-sample-sample />
  </div>
</template>
