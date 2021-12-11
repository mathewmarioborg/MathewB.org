<template>
  <div class="container">
    <div class="outer-container">
      <div class="inner-container">
        <div style="padding: 1em">
          <h3 style="color: #559B81">{{ title }}</h3>
          <p style="color: aliceblue">{{body}}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "information.vue",
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
  padding: 1em;
  display: flex;
  flex-direction: row;
  justify-content: center;
  text-align: left;
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
  padding-bottom: 0.5em;
}
</style>
