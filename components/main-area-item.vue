<template>
	<view class="main-area-item">
		<view class="concrete-title">{{title}}</view>
		<slot>
			<input class="content" placeholder="请输入"/>
		</slot>
	</view>
</template>

<script>
	export default {
		name:"main-area-item",
		props:{
			title:{
				type:String,
				default:'默认标题'
			}
		},
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	.main-area-item{
		margin-top: 20rpx;
	}
.concrete-title{
		font-weight: 700;
		font-size: 30rpx;
	}
	.concrete-title::before{
		content: '*';
		color: red;
		font-weight: 700;
	}
	
	.content{
		border-bottom: 1rpx solid #ccc;
		padding: 20rpx 0;
		font-size: 30rpx;
		color: #999;
	}
</style>