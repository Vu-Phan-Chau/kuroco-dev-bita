<template>
  <div>
    <h1>Develop</h1>
    <h2>Title demo</h2>
    <p>API SECRET: {{ $config.API_SECRET }}</p>
    <Tutorial />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
