<template>
  <div class="main">
    <div class="header">
      <img
        src="https://avatars2.githubusercontent.com/u/26364692?s=460&u=b308540b46fb5db07c237d3baa578cda8f4f0ddd&v=4"
        alt="Picture of Calvin Schröder"
      />
      <div class="relative">
        <h1 class="main-1 title">Calvin Schröder</h1>
      </div>
    </div>
    <div class="appearing-text">
      <div class="main-2 div-withoutbreak">
        is <strong>architecting</strong> and <strong>developing</strong>
      </div>
      <div class="main-3 div-withoutbreak">
        fullstack Web-Applications, in Agile environments!
      </div>
      <div class="main-4 telekom-it">
        Currently
        <b-link
          class="text-decoration-none"
          href="https://www.telekom.com/de/karriere/fokusthemen/telekom-it"
          ><strong>@Deutsche Telekom IT</strong></b-link
        >
      </div>
    </div>
  </div>
</template>

<style>
.telekom-it {
  padding: 25px;
  font-family: 'TeleGroteskNext', Calibri, 'PT Sans Narrow', sans-serif;
  font-size: 40px;
  text-decoration: none;
}
.telekom-it a {
  color: #e20074;
  background-color: #ffffff;
  border-radius: 15px;
  padding: 7px;
}
.main {
  width: 100%;
}
.div-withoutbreak {
  display: inline;
  font-size: 60px;
}
.relative {
  display: flex;
  flex-direction: column;
}
.header {
  position: relative;
  float: left;
  width: 100%;
}
.header img {
  padding-top: 20px;
  height: 300px;
  border-radius: 70%;
  float: left;
}

.main-1 {
  --time: 2s;
  width: 100%;
  position: absolute;
  bottom: 0;
  opacity: 0;
  -moz-animation: fadein 1s ease-in var(--time) forwards; /* Firefox */
  -webkit-animation: fadein 1s ease-in var(--time) forwards; /* Safari and Chrome */
  -o-animation: fadein 1s ease-in var(--time) forwards; /* Opera */
  animation: fadein 1s ease-in var(--time) forwards;
}

.main-2 {
  --time: 4s;
  clear: left;
  opacity: 0;
  -moz-animation: fadein 1s ease-in var(--time) forwards; /* Firefox */
  -webkit-animation: fadein 1s ease-in var(--time) forwards; /* Safari and Chrome */
  -o-animation: fadein 1s ease-in var(--time) forwards; /* Opera */
  animation: fadein 1s ease-in var(--time) forwards;
}

.main-3 {
  --time: 5.5s;
  opacity: 0;
  -moz-animation: fadein 1s ease-in var(--time) forwards; /* Firefox */
  -webkit-animation: fadein 1s ease-in var(--time) forwards; /* Safari and Chrome */
  -o-animation: fadein 1s ease-in var(--time) forwards; /* Opera */
  animation: fadein 1s ease-in var(--time) forwards;
}

.main-4 {
  --time: 7s;
  opacity: 0;
  -moz-animation: fadein 1s ease-in var(--time) forwards; /* Firefox */
  -webkit-animation: fadein 1s ease-in var(--time) forwards; /* Safari and Chrome */
  -o-animation: fadein 1s ease-in var(--time) forwards; /* Opera */
  animation: fadein 1s ease-in var(--time) forwards;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}

@-moz-keyframes fadein {
  /* Firefox */
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadein {
  /* Safari and Chrome */
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-o-keyframes fadein {
  /* Opera */
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style>
