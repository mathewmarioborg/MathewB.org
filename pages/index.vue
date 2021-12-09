<template>
  <div class='page'>
    <PageHeader title="Mathew Borg" subtitle="My Personal Portfolio"/>
    <container1 class='container' title='Test 1' body='Test 222222222222222222222222222222222222222222222222222222222222  info'/>
    <container1 title="Test 2" img='Mathew_Borg_Final_White.jpg' body="testvfkjrebhvpkj fvneovneroibv e erer ger oiergiouergjheroig eri gergirtbrtnrfgnghfnghfnghfnghfn thtr htreh rh rthrt hyrt htrreogie egoer go eirger gerig erf hdsfh dskjfh sdkfh skf shjkfsdhkjf hsdkf hskdfh kjsdkjkjlsdafl kg"/>
    <container2 title="Test 3" img='Mathew_Borg_Final_White.jpg' body="testvfkjrebhvpkj fvneovneroibv e erer ger oiergiouergjheroig eri gergirtbrtnrfgnghfnghfnghfnghfn thtr htreh rh rthrt hyrt htrreogie egoer go eirger gerig erf hdsfh dskjfh sdkfh skf shjkfsdhkjf hsdkf hskdfh kjsdkjkjlsdafl kg"/>
    <container3 title="Test 4" img='Mathew_Borg_Final_White.jpg' body="testvfkjrebhvpkj fvneovneroibv e erer ger oiergiouergjheroig eri gergirtbrtnrfgnghfnghfnghfnghfn thtr htreh rh rthrt hyrt htrreogie egoer go eirger gerig erf hdsfh dskjfh sdkfh skf shjkfsdhkjf hsdkf hskdfh kjsdkjkjlsdafl kg"/>

  </div>
</template>

<script>
import Container1 from '../components/container1'
import PageHeader from "../components/PageHeader";

export default {
  components: {PageHeader, Container1 }
}
</script>

<style>
.page{
  display: flex;
  flex-direction: column;
  -ms-flex-align: center;
}
</style>
