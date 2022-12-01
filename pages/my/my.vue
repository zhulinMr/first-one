<template>
	<view>
		<view class="my-login">
			<login></login>
		</view>
	</view>
</template>

<script>
	import login from"@/pages/my/components/i-login.vue"
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		},
		components:{
			login
		}
	}
</script>

<style lang="scss">
	
	.my-login{
		height: 350rpx;
		background-color:#5ccc84 ;
		border-bottom-left-radius: 100rpx;
	}

</style>
