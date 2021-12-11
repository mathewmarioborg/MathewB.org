<template>
  <div class='page-container'>
    <PageHeader title="Mathew Borg" subtitle="My Personal Portfolio"/>
    <textBox :image="require(`~/assets/IMG-005-Graffiti Mathew_2021-08-20.jpg`)" title="Test" body="test2"></textBox>
    <textBox title="Test" body="test2"></textBox>
    <textBoxRight title="testOne" body="testTwo" :image="require(`~/assets/IMG-005-Graffiti Mathew_2021-08-20.jpg`)"></textBoxRight>
    <textBoxLeft title="TestOneMillion" body="testTwoMillion" :image="require(`~/assets/IMG-001-Graffiti Mathew_2021-08-20.jpg`)"></textBoxLeft>
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

.goal-container {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding-bottom: 0.5em;
}
</style>
