<template>
  <div id="footer">
    <span id="footer-findme">Find me on:</span> <br />
    <SocialMedia />
    <hr />
    <a href="/" class="footer-link"> Home </a>
    <a href="/cv" class="footer-link"> Curriculum Vitae </a>
    <a href="/imprint" class="footer-link"> Imprint </a>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
hr {
  border: 1px solid #ffffff;
}
#footer-findme {
  font-size: 30px;
}
.footer-link:hover {
  color: #e20074;
  text-decoration: none;
}
.footer-link {
  padding: 5px;
  font-size: 30px;
  color: white;
  text-decoration: none;
}
.links {
  padding-top: 15px;
}

#footer {
  margin-top: 15%;
  width: 100%;
}
</style>
