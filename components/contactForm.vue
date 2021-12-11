<template>
  <div class="container">
    <div class="outer-container">
    <form name="myForm" class="form-container">
      <h1 class="title">Crispy Mint Diled Contact Form</h1>
      <p>Name:</p>
      <input class="textInput" type="text" ref="name" name="name">
      <p>Email:</p>
      <input class="textInput" type="text" ref="email" name="email">
      <p>Country:</p>
      <select class="textInput" ref="country" name="country">
        <option value="-1" selected>[choose yours]</option>
        <option value="1">USA</option>
        <option value="2">UK</option>
        <option value="3">INDIA</option>
      </select>
      <p>Message:</p>
      <textarea class="textInput" type="text" ref="message" name="message" cols="40"/>
      <button v-on:click="validate()" type="button">Login</button>
    </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "contactForm",
  methods:{
    async validate(){
      if (document.myForm.name.value === ""){
        alert("Please provide your Name!");
        document.myForm.name.focus();
        return false;
      }if (document.myForm.email.value === "") {
        alert("Please provide your Email!");
        document.myForm.email.focus();
        return false;
      }if (document.myForm.country.value === "-1") {
        alert("Please provide your Country!");
        document.myForm.country.focus();
        return false;
      } if (document.myForm.message.value === ""){
        alert("Please provide a message!");
        document.myForm.message.focus();
        return false;
      } await this.sendForm();
    },
    async sendForm(){
      console.log("send!!!")
      //comming soon
    }
  }
}


</script>

<style scoped>
.container {
  padding: 2em;
  display: flex;
  flex-direction: row;
  justify-content: center;
  text-align: center;
}
.outer-container{
  width: 80%;
  background-color: #559B81;
}
.form-container {
  background-color: #243742;
  margin-left: 1em;
  margin-right: 1em;
  display: flex;
  flex-direction: column;
  padding-bottom: 2em;
}
.title {
  font-style: italic;
  color: aliceblue;
  padding: 0.5em 1em 0.5em 1em;
}
.textInput {
  border-radius: 0.5em;
  border: darkgray;
  background-color: darkgray;
  display: block;
  margin-right: auto;
  margin-left: auto;
  height: 2em;
  width: 16em;
  outline: none;
  margin-bottom: 1em;
  text-align: center;
}

button {
  width: 10em;
  border-radius: 0.5em;
  display: inline-block;
  margin-right: auto;
  margin-left: auto;
  background-color: #35495e;
  border: solid #35495e;
  outline: none;
  color: aliceblue;
}
button:hover {
  background-color: transparent;
  color: aliceblue;
}

p{
  color: aliceblue;
  padding: 0.2em;
}

</style>
