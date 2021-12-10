<template>
  <div class='page-container'>
    <PageHeader title="Mathew Borg" subtitle="My Personal Portfolio"/>
    <textBox :image="require(`~/assets/IMG-005-Graffiti Mathew_2021-08-20.jpg`)" title="Test" body="test2"></textBox>
  </div>
</template>

<script>
import PageHeader from "../components/PageHeader";
import textBox from "@/components/textBox";

export default {
  components: {PageHeader, textBox}
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
