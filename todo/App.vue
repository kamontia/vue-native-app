<template>
  <view>
    <button v-bind:title="message" v-bind:on-press="handleBtnPress"/>
  </view>
</template>

<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}
</style>

<script>
export default {
  data: function() {
    return {
      message: "Hello World"
    };
  },
  methods: {
    handleBtnPress: function() {
      alert('Btn Press');
    }
  }
};
</script>

