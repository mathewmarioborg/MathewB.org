<template>
  <div class="page">
    <PageHeader title="Affiliations" subtitle="All My Affiliates"/>
    <textBoxRight title="Ethan Munsterman Photography corp." body="All Images used in this website have been created by Ethan Munsterman Photography corp. All rights are reserved to Borg Development corp. and Ethan Munsterman Photography corp. All materials, designs, text and images contained in the Website (collectively, the “Materials”) are copyrighted property of Borg Development Corp. or related entities such as Ethan Munsterman Photography corp. and Borg Development Corp. neither warrants nor represents that your use of these Materials will not infringe rights of third parties unrelated to Borg Development Corp." :image="require(`~/assets/IMG-001-Graffiti Ally Ethan_2021-08-20.jpg`)"></textBoxRight>
  </div>
</template>

<script>
export default {
  name: "affiliations"
}
</script>

<style scoped>
.page{
  display: flex;
  flex-direction: column;
  -ms-flex-align: center;
}
</style>
