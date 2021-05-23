<template>
  <div>
    <!-- Header container -->
    <Header />
    <Home />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Home from "@/components/Home";
export default {
  name: "App",
  components: { Header, Home },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

ul[class],
ol[class] {
  padding: 0;
}

body,
h1,
h2,
h3,
h4,
p,
ul[class],
ol[class],
li,
figure,
figcaption,
blockquote,
dl,
dd {
  margin: 0;
}

body {
  min-height: 100vh;
  text-rendering: geometricPrecision;
  line-height: 1.5;
}

html {
  scroll-behavior: smooth;
}

ul[class],
ol[class] {
  list-style: none;
}

a:not([class]) {
  text-decoration-skip-ink: auto;
}

img {
  max-width: 100%;
  display: block;
}

input,
button,
textarea,
select {
  font: inherit;
}

@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}

html {
  position: relative;
  font-family: "Montserrat", sans-serif;
  font-size: 4.75vw;
}
@media (min-width: 600px) {
  html {
    font-size: 2.5vw;
  }
}
@media (min-width: 1000px) {
  html {
    font-size: 1.5vw;
  }
}
@media (min-width: 1200px) {
  html {
    font-size: 18px;
  }
}
@media (min-width: 1600px) {
  html {
    font-size: 24px;
  }
}

body {
  position: relative;
  color: #ffffff;
  overflow-x: hidden;
}

.nowrap {
  white-space: nowrap;
}

@media (min-width: 1000px) {
  .mobile-only {
    display: none !important;
  }
}

.desktop-only {
  display: none !important;
}
@media (min-width: 1000px) {
  .desktop-only {
    display: block !important;
  }
}
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
</style>
