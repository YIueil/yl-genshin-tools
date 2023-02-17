<template>
	<view class="content">
		<view class="banner"></view>
		<view class="user_profile">
			<text class="title">{{title}}</text>
		</view>
		<view>
			<text class="title">数据总览</text>
		</view>
		<view>
			<text class="title">我的角色</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '首页'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.banner {
		width: 750rpx;
		height: 324rpx;
		background-image: linear-gradient(to top, #FFFFFF, transparent), url("https://uploadstatic.mihoyo.com/puzzle/upload/puzzle/2023/01/16/08d58aa715b63ba1af11b32975bb4306_7778594134913602338.jpg?x-oss-process=image/format,webp/quality,Q_90");
		background-size: cover
	}
	
	.user_profile {
		position: relative;
		width: 700rpx;
		height: 150rpx;
		margin: -75px auto;
		border: 1px solid black;
	}
	
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
