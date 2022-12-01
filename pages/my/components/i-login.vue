<template>
	<view >
		<view class="i-login">
			<view class="image"></view>
			<view class="i-login-right">
				<view>立即登录</view>
				<text>登录解锁更多功能</text>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
	.i-login{
		width:  696rpx;
		height: 123rpx;
		padding: 30rpx;
		display: flex;
		color: #fff;
		
		.image{
			width: 120rpx;
			height: 120rpx;
			border-radius: 50%;
			background-color: #fff;
		}
		.i-login-right{
			display: flex;
			flex-direction: column;
			padding-left: 30rpx;
			view{
				font-size: 34rpx;
				margin-bottom: 20rpx;
			}
			text{
				font-size: 24rpx;
			}
		}
	}
</style>