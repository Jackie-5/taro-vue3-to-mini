<template>
  <view class="red">
    <view>Picker: {{title}}</view>
    <view v-for="item in list">PickerItem: {{item}}</view>
    <button @tap="onButtonClick">Click me</button>

    <view>====NutUI====</view>
    <nut-button type="primary">主要按钮</nut-button>
    <nut-button type="info">信息按钮</nut-button>
    <nut-button type="default">默认按钮</nut-button>
    <nut-button type="danger">危险按钮</nut-button>
    <nut-button type="warning">警告按钮</nut-button>
    <nut-button type="success">成功按钮</nut-button>
  </view>
</template>

<script lang="ts">
  export default {
    setup() {
      return {
        title: 'asdfas',
      }
    }
  }
</script>

<style lang="scss">
.red {
  color: red
}
</style>
