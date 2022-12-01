<template>
	<view>
		<view class="my-login">
			<!-- 登录 -->
			<login></login>
			<!-- 分类 -->
			<tab></tab>
			<list :list="list"></list>
		</view>
	</view>
</template>

<script>
	import login from"@/pages/my/components/i-login.vue"
	import tab from "@/pages/my/components/tab.vue"
	import list from "@/components/i-list.vue"
	import myListBar from "@/config/my-list-bar.js"  //数据
	export default {
		data() {
			return {
				list:myListBar()
			}
		},
		methods: {
			
		},
		components:{
			login,
			tab,
			list
		}
	}
</script>

<style lang="scss">
	
	.my-login{
		height: 350rpx;
		background-color:#5ccc84 ;
		border-bottom-left-radius: 100rpx;
		border-bottom-right-radius: 100rpx;
	}

</style>
