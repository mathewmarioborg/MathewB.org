<template>
  <div class="nav">
    <a href="/" class="link">Home</a>
    <a href="/about" class='link'>About</a>
    <a herf="/portfolio" class='link'>Portfolio</a>
    <a href="/contact" class='link'>Contact</a>
  </div>
</template>

<script>
export default {
  name: 'navbar'
}
</script>

<style scoped>
  .nav {
    display: flex;
    justify-content: center;
    padding: 1em;
    gap: 2em;
    width: 100%;
    height: 4em;
    background-color: #35495e;
  }
  .link {
    text-decoration: none;
    color: aliceblue;
    font-size: 1.25em;
  }
  .link:hover {
    color: #559B81;
  }
</style>
