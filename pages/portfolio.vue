<template>
  <div class="page-container">
    <PageHeader title="Portfolio" subtitle="A Compilation Of All My Work"/>
    <TextBoxLeft title="Web Development" body="This website you are currently visiting has been coded using the nuxt.js framework which was built off of vue.js. This has been done to show my abilities of using html css and custom web frameworks. This site is used to prove that I can use html and other web tools to construct a website. In addition to this I have also done web work using wordpress and php programming. That website was made to be a skeleton of this website so all the information will be identical but the layout and web design will be different. wp.mathewborg.com was also made to show my clients an example of a website that I could create for them. I also own borgdevelopment.ca and this is my main website for my business Borg Development. That site has also been designed using wordpress to show my clients another example of a website I can create. I also own a third domain mathewb.org which I use for testing all kinds of web projects so feel free to check it out and see what i'm currently working on." :image="require(`~/assets/IMG-003-Graffiti Mathew_2021-08-20.jpg`)"/>
    <TextBoxRight title="First Robotics" body="Robotics has become one of my greatest passions over the last 4 years of my life. Ever since I joined the First Robotics Team 7200 in 2018 I have taken such an interest in robotics and invested many hours of my life working on robotic technologies. The thing I love most of all about robotics is programming. I have always been fascinated on how programming can make things work and how there are different methods to make things run more effectively. Within my last 4 years on First Robotics Team 7200 I have increased my knowledge on java programing, autonomous vision systems, and even learned about how to apply physics to robotic programming." :image="require(`~/assets/IMG-004-Graffiti Mathew_2021-08-20.jpg`)"/>
  </div>
</template>

<script>
import PageHeader from "@/components/PageHeader";
import textBox from "@/components/textBox";
import textBoxRight from "@/components/textBoxRight";
import textBoxLeft from "@/components/textBoxLeft";
export default {
  components: {PageHeader, textBox, textBoxRight, textBoxLeft},
  name: 'portfolio'
}
</script>

<style scoped>

</style>
