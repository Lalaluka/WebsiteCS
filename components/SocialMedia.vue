<template>
  <div class="nobreak">
    <a
      href="http://www.twitter.com/cal_schroeder"
      target="_blank"
      class="socialicon text-3d"
    >
      <font-awesome-icon :icon="['fab', 'twitter']" />
    </a>
    <a
      href="https://www.instagram.com/calvin.schroeder98/?hl=de"
      target="_blank"
      class="socialicon text-3d"
    >
      <font-awesome-icon :icon="['fab', 'instagram']" />
    </a>
    <a
      href="https://www.linkedin.com/in/calvin-schröder-0b5468178?originalSubdomain=de"
      target="_blank"
      class="socialicon"
    >
      <font-awesome-icon :icon="['fab', 'linkedin']" />
    </a>
    <a href="https://github.com/Lalaluka" target="_blank" class="socialicon">
      <font-awesome-icon :icon="['fab', 'github']" />
    </a>
  </div>
</template>

<style>
.socialicon {
  height: 100px;
}
.socialicon:hover {
  color: #e20074;
}
.socialicon {
  padding: 5px;
  font-size: 80px;
  color: white;
  text-decoration: none;
}
.nobreak {
  display: inline;
}
</style>
