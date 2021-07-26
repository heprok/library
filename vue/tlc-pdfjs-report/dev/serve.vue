<script>
import Vue from 'vue';
import TlcPdfjsReport from '@/tlc-pdfjs-report.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    TlcPdfjsReport
  }
});
</script>

<template>
  <div id="app">
    <tlc-pdfjs-report />
  </div>
</template>
