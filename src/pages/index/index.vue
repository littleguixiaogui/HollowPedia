<template>
  <view class="story_page">

    <!-- section mian content -->
    <view class="main_content">
      <view class="main_content_title">Main Content</view>
      <view class="section_devider"></view>
      <image class="main_img" src="/static/White_Palace_Centre_Exit.webp" alt="White Palace Centre Exit image"></image>      
      <view class="main_content_description">
        <view>The White Palace is an area in the Dream Realm. It used to be the palace of the Pale King but now primarily contains platforming challenges.</view>
      </view>
    </view>

    <!-- section reference -->
    <view class="reference">
      <view class="reference_title">Reference</view>
      <view class="section_devider"></view>
      <view class="reference_description"> 💠 Hollowknight.fandom.com</view>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
    }
  },
  onLoad() {},
  methods: {},
}
</script>

<style scoped>
/* section devider line */
.section_devider {
  height: 1px;
  background-color: #e0e0e0;
  margin: 10px 0;
}
/* storage */
.story_page {
  padding-top: 20rpx;
   gap: 40rpx;
}
.main_content_description {
  display: flex;
  flex-direction: column;
  padding: 0 20px;
}
.main_img{
  width: 100%;
}
.main_img_description {
  font-size: 24rpx;
  color: #8f8f94;
  align-self: center;
}
</style>
