<template>
  <view class="content">
    <view class="text">家用助手</view>
    <button open-type="contact">打开客服</button>
  </view>
</template>

<script setup lang="ts">
import {ref} from 'vue'

const title = ref('Hello')
</script>

<style lang="scss" scoped>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100vw;
  height: 100vh;

  .text {
    margin-bottom: 100rpx;
    font-size: 40rpx;
    font-weight: bold;
  }
}
</style>
