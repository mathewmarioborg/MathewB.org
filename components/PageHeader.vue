<template>
  <div>
    <h1>{{title}}</h1>
    <p>{{subtitle}}</p>
    <hr>
  </div>
</template>

<script>
export default {
  name: "PageHeader",
  props: {
    title: {
      type: String,
    },
    subtitle:{
      type: String,
    }
  }

}
</script>

<style scoped>
  h1 {
    text-align: center;
    padding-top: 0.5em;
    font-size: 36px;
    color: aliceblue;
    letter-spacing: 4px;
  }

  p {
    text-align: center;
    font-size: 18px;
    color: aliceblue;
    letter-spacing: 4px;
  }

  hr {
    width: 60%;
    display: block;
    margin: 0.5em auto;
    border: none;
    height: 3px;
    border-radius: 2px;
    background-color: #35495e;
  }

</style>
