<script setup lang="ts"></script>

<template>
  <div class="home">
    <div class="d-flex justify-content-center">
      <BotList />
    </div>
    <hr />
    <!-- <img alt="RichMaster logo" src="../assets/richmaster-logo.png" width="450px" class="my-5" /> -->
    <div title="RichMaster logo" class="logo-svg my-5 mx-auto" />
    <div>
      <h1>RichMaster - Home for AI driven investment</h1>
    </div>
    <br />
    <div>Leverage the cutting-edge AI technologies to help you increase profit and reduce risk!</div>
    <br />
    <p>Led by former department head of computer science, HKU and fintech experts</p>
  </div>
</template>

<style lang="scss" scoped>
.home {
  margin-top: 1.5em;
}
.logo-svg {
  -webkit-mask: url(../assets/richmaster-logo.png) no-repeat center;
  -webkit-mask-size: 240px 240px;
  mask: url(../assets/richmaster-logo-mask.png) no-repeat center;
  mask-size: contain;
  width: 250px;
  height: 250px;
}
</style>
