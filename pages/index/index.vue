<template>
	<view class="">
		<view class="title">
			杭州方大丝绸有限公司<br/>
			应聘登记表
		</view>
		<view class="main-area">
			<main-area-item title='应聘岗位'>
			</main-area-item>
			<main-area-item title='填表日期'></main-area-item>
			<main-area-item title='姓名'></main-area-item>
			<main-area-item title='性别'></main-area-item>
			<main-area-item title='出生日期'></main-area-item>
			<main-area-item title='民族'></main-area-item>
			<main-area-item title='政治面貌'></main-area-item>
			<main-area-item title='婚否'></main-area-item>
			<main-area-item title='健康状况'></main-area-item>
			<main-area-item title='籍贯(省/市)'></main-area-item>
			<main-area-item title='联系方式'></main-area-item>
			<main-area-item title='电子邮箱'></main-area-item>
			<main-area-item title='学历'></main-area-item>
			<main-area-item title='现住地'></main-area-item>
			<main-area-item title='目前是否在职'></main-area-item>
			<main-area-item title='预计到岗时间'></main-area-item>
			<main-area-item title='期望薪资'></main-area-item>
			<main-area-item title='外语水平'></main-area-item>
			<main-area-item title='计算机水平'></main-area-item>
			<main-area-item title='教育经历(请至少完整填写一行)'></main-area-item>
			<main-area-item title='工作经历(请至少完整填写一行,没有则写'无')'></main-area-item>
			<main-area-item title='计算机水平'></main-area-item>
		</view>
	</view>
</template>

<script>
	import mainAreaItem from 'components/main-area-item.vue'
	export default {
		components:{
			mainAreaItem
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.title{
		background-color: #7298bf;
		width: 100%;
		font-size: 34rpx;
		text-align: center;
		color: #fff;
		padding: 10rpx 0;
	}
	
	.main-area{
		box-sizing: border-box;
		padding-left: 30rpx;
	}
</style>
