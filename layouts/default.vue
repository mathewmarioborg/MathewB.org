<template>
  <div class="layout-container">
    <Navbar></Navbar>
    <main class="content-container">
      <Nuxt></Nuxt>
    </main>
    <Footer></Footer>
  </div>
</template>

<style>

.layout-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
html {
  font-family: 'Source Sans Pro',
  -apple-system,
  BlinkMacSystemFont,
  'Segoe UI',
  Roboto,
  'Helvetica Neue',
  Arial,
  sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #243742;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
.content-container {
  background-color: #2b3c47;
  width: 80%;
  margin-left: auto;
  margin-right: auto;
  min-height: 100%;
  flex-grow: 1;
  justify-self: center;
}

</style>
<script>
import Footer from "../components/footer";
export default {
  components: {Footer}
}
</script>
