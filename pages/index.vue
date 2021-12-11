<template>
  <div class='page-container'>
    <PageHeader title="Mathew Borg" subtitle="My Personal Portfolio"/>
    <textBoxRight title="Welcome To MathewBorg.com" body="This website you are currently visiting has been coded using the nuxt.js framework which was built off of vue.js. This has been done to show my abilities of using html css and custom web frameworks. This site is used to prove that I can use html and other web tools to construct a website. In addition to this I have also done web work using wordpress and php programming. " :image="require(`~/assets/IMG-001-Graffiti Mathew_2021-08-20.jpg`)"/>
    <textBoxLeft title="My Background Information" body="My name is Mathew Borg and I’m 18 years old. I have created this website to demonstrate my web development abilities and as a master portfolio to show off all my work. I have taken part in many great projects in my life thus far and I will continue to involve myself in projects to increase my knowledge and make a difference in the world." :image="require(`~/assets/IMG-002-Graffiti Mathew_2021-08-20.jpg`)"/>
    <song></song>
  </div>
</template>

<script>
import PageHeader from "../components/PageHeader";
import textBox from "@/components/textBox";
import textBoxRight from "@/components/textBoxRight";
import textBoxLeft from "@/components/textBoxLeft";

export default {
  components: {PageHeader, textBox, textBoxRight, textBoxLeft}
}
</script>

<style>

</style>
