<template>
	<view class="tab">
		<view class="i-tab">
			<view class="box">
				<view class="content" v-for="item,index in list" :key="item.id">
					<text :class="item.iconfont"></text>
					<view>{{item.text}}</view>
				</view>
			</view>
			
			
		</view>
	</view>
</template>

<script>
	export default{
		data(){
			return{
				list:[
					{
						text:"订单",
						iconfont:"iconfont icon-OrderHistory",
						id:1
					},
					{
						text:"消息",
						iconfont:"iconfont icon-pinglun2",
						id:2
					},
					{
						text:"收藏",
						iconfont:"iconfont icon-shoucang1",
						id:3
					},
					{
						text:"在学",
						iconfont:"iconfont icon-e-learning-monitor",
						id:4
					},
				]
			}
		}
	}
</script>

<style lang="scss">
	.tab{
		padding: 30rpx;
	}
	.i-tab{
		width: 690rpx;
		height: 144rpx;
		background-color: #fff;
		border-radius: 8rpx;
		display: flex;
		flex-direction: row;
		align-items: center;
		.box{
			width: 100%;
			display: flex;
			justify-content: space-around;
		}
		.content{
			flex: 1;
			padding: 30rpx 0;
			text-align: center;
			
			text{
				
				font-size: 40rpx;
				color: #febf0d;
				
			}
			view{
				color: #6c757d;
				font-size: 24rpx;
				margin-top: 10rpx;
			}
		}
	}
</style>