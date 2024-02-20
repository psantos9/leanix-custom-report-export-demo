<template>
  <div>Custom Report Export Demo</div>
</template>

<script lang="ts" setup>
import '@leanix/reporting'
;(async () => {
  await lx.init()
  const reportSetup: lxr.ReportConfiguration = {
    export: {}
  }
  await lx.ready(reportSetup)
})()
</script>
