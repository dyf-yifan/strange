<template>
	<view class="content">
		<h2>music</h2>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view>
		<myaudio></myaudio>
	</view>
</template>

<script>
	import Myaudio from '@/components/myaudio.vue'
	export default {
		components:{
			Myaudio
		},
		data() {
			return {
				title: '音频组件开发'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
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