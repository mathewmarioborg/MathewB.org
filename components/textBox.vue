<template>
  <div class="container">
    <div class="outer-container">
      <div class="text-container">
        <h1 class="title">{{ title }}</h1>
        <p class="text">{{body}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "textBox",
  props: {
    title: {
      type: String,
      required: true
    },
    body: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}
.outer-container{
  width: 80%;
  background-color: #559B81;
  text-align: center;
}
.text-container {
  margin-left: 1em;
  margin-right: 1em;
  background-color: #243742;
  color: aliceblue;
  padding: 1em;
}
.title {
  font-style: italic;
  margin-top: 0.1em;
  margin-bottom: 0.1em;
  padding: 0;
}
@media all and (max-width: 1100px) {
  .box {
    max-width: 80%;
  }
}
</style>

