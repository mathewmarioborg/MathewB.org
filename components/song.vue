<template>
  <div class="container">
    <div class="outer-container">
      <div class="inner-container">
        <h1 class="title">{{ title }}</h1>
        <iframe width="420" height="315" :src="video"></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "song",
  props: {
    title: {
      type: String,
      required: true
    },
    video: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.container {
  padding: 1em;
  display: flex;
  flex-direction: row;
  justify-content: center;
  text-align: center;
}
.outer-container{
  width: 80%;
  background-color: #559B81;
}
.inner-container {
  background-color: #243742;
  margin-left: 1em;
  margin-right: 1em;
  display: flex;
  flex-direction: column;
  padding: 1em;
  align-items: center;
}
.title {
  font-style: italic;
  margin-bottom: 0.1em;
  padding: 0;
  color: aliceblue;
}
</style>
