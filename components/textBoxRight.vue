<template>
  <div class="container">
    <div class="outer-container">
      <div class="text-container">
        <div class="txt">
          <h1 class="title">{{ title }}</h1>
          <p class="text">{{body}}</p>
        </div>
        <img :src="image" alt="Mathew Borg" width="30%" height="30%">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "textBoxRight",
  props: {
    title: {
      type: String,
      required: true
    },
    body: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: false
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
  display: flex;
  flex-direction: row;
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
.txt{
  width: 70%;
  padding-right: 1em;
}

</style>
