<template>
  <div class='page'>
    <div class='test1'>
      <container1 class='test1' title='Test 1' body='Test 222222222222222222222222222222222222222222222222222222222222  info'/>
    </div>
  </div>
</template>

<script>
import Container1 from '../components/container1'
export default {
  components: { Container1 }
}
</script>

<style>

.test1 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

</style>
