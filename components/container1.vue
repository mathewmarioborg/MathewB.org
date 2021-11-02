<template>
  <div class="container">
    <div class="outer-container">
      <div class="text-container">
        <img class='img' src={{ URL }}/>
        <h1 class="title">{{ title }}</h1>
        <p class="text">{{body}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'container1',
  props:{
    title:{
      type: String,
      required: true
    },
    body:{
      type: String,
      required: true
    },
    URL:{
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
  margin-left: 1em;
  margin-right: 1em;
  background-color: #243742;
  color: aliceblue;
  padding: 0.3em 1em;
}
.title {
  font-style: italic;
  margin-top: 0.1em;
  margin-bottom: 0.1em;
  padding: 0;
}

</style>
