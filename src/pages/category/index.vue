<template>
    <view class="container">
        <!-- 搜索栏 -->
    <view class="search">
    <!-- 搜索栏标签 -->
    <view class="input-box">
<input type="text">
    </view>
    <!-- 搜索的结果 -->
      <view class="content"></view>
     </view>
    </view>
</template>
<script>
export default {
    data(){
        return{
            "navigationBarTitleText":"商品分类"
        }
    }
}
</script>

<style>
    .search .input-box{
        background-color: #f0f0f0;
        padding: 10rpx 20rpx;
    }
    .search .input-box input{
        background-color: #fff;
        border-radius:20rpx;
    }
</style>