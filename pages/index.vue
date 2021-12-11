<template>
  <div class='page-container'>
    <PageHeader title="Mathew Borg" subtitle="My Personal Portfolio"/>
    <textBoxRight title="Welcome To MathewBorg.com" body="This website you are currently visiting has been coded using the nuxt.js framework which was built off of vue.js. This has been done to show my abilities of using html css and custom web frameworks. This site is used to prove that I can use html and other web tools to construct a website. In addition to this I have also done web work using wordpress and php programming. I am currently attending Humber College and I am currently working towards getting an advanced diploma in computer programming & analysis. I was born in Alliston Ontario, but I have grown up in Beeton my whole life. My cultural background is Maltese and Italian. I have many strengths and good qualities but the strengths that I am most proud of are: my computer programming, photography and video editing skills. These are areas of strengths for me because they allow me to be creative while still using critical thinking skills. I love being challenged and coming up with different ways to look at situations while solving challenges. I always make an effort to push myself to work hard so that I can achieve my goals." :image="require(`~/assets/IMG-001-Graffiti Mathew_2021-08-20.jpg`)"/>
    <textBoxLeft title="My Background Information" body="My name is Mathew Borg and I’m 18 years old. I have created this website to demonstrate my web development abilities and as a master portfolio to show off all my work. I have taken part in many great projects in my life thus far and I will continue to involve myself in projects to increase my knowledge and make a difference in the world.  The Strengths and skills I have are my computer programming, web development and skills in small electrical components. These are my areas of strengths because they are some of the things I love working on in my spare time which allows me to be creative and challenge my thinking skills. With these skills I am often faced with challenges and whenever a challenge comes up in my life I will never give up on it and I will work on it until I overcome it. I love challenges because  they force me to come up with different ways to look at situations and push me to learn more information." :image="require(`~/assets/IMG-002-Graffiti Mathew_2021-08-20.jpg`)"/>
    <song title="My Current Favorite Song" video="https://www.youtube.com/embed/_Yhyp-_hX2s"></song>
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
