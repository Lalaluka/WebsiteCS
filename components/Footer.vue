<template>
  <div id="footer">
    <SocialMedia />
    <b-link href="/imprint" rel="noopener noreferrer"> Imprint </b-link>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
.b-link {
  display: inline;
}
.links {
  padding-top: 15px;
}

#footer {
  position: fixed;
  bottom: 0px;
  height: auto;
  width: 100%;
}
</style>
