<template>
	<view class="content">
		<!-- 轮播图 -->
		<swiper class="picture" indicator-dots circular>
		<swiper-item >
			<image src="../../static/image/fenl1.jpg"/>
		</swiper-item>
		<swiper-item>
			<image src="../../static/image/fenl2.jpg"/>
		</swiper-item>
		<swiper-item>
			<image src="../../static/image/fenl3.jpg"/>
		</swiper-item>
		</swiper>
		<view class="q">
		<view class="w">超低价格</view>
		<view class="w">专属福利</view>
		<view class="w">赚取积分</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '',
				"previous-margin":"5rpx"
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang='less'>
.content .picture{
height: 300rpx;
image {
	width: 750rpx;
    height: 300rpx;
  }
}

.q{
display: flex;
.w{
	flex: 1;
	text-align: center;
	color: coral;
}
}

</style>
