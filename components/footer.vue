<template>
  <footer>
    <h4>Developed by <a href="https://www.borgdevelopment.ca">Borg Development</a>, corp. All Rights Reserved &copy; <span id="year"></span> | <a href="/terms">Terms of Use</a> | <a href="/affiliations">Affiliations</a></h4>
    <h4 class="link"><a href="https://github.com/mat4539/MathewB.org">Check Out The Source Code!</a></h4>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
if (typeof window !== 'undefined') {
  document.getElementById("year").innerHTML = new Date().getFullYear();
}
</script>


<style scoped>
footer {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  color: #5e6f88;
  text-align: center;
  height: 4em;
}

a {
  color: #7d8ba2;

}
</style>
