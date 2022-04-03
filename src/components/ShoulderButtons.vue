<template>
  <div class="shoulder-buttons">
    <div class="left">
      <BasicButton class="button" color="#ed6d00" shape="square" type="LEFT_SHOULDER">LB</BasicButton>
      <BasicButton class="button" color="#009ea9" shape="square" type="LEFT_TRIGGER">LT</BasicButton>
    </div>
    <div class="right">
      <BasicButton class="button" color="#009ea9" shape="square" type="RIGHT_TRIGGER">RT</BasicButton>
      <BasicButton class="button" color="#ed6d00" shape="square" type="RIGHT_SHOULDER">RB</BasicButton>
    </div>
  </div>
</template>

<script>
import BasicButton from "./BasicButton.vue"
export default {
  name: 'ShoulderButtons',
  components: { BasicButton },
}
</script>

<style scoped>
.shoulder-buttons {
  display: flex;
  justify-content: space-between;
}
.left {
  display: flex;
}
.right {
  display: flex;
}
  .button {
    width: 100px;
    height: 30px;
    line-height: 30px;
  }
</style>
