<template>
	<view>
		<view class="index-list">
			<view class="index-list1">
				<view class="left">
					<image src="../../static/demo/userpic/1.jpg"
					mode="widthFix"
					lazy-load></image>
					<view class="name">
						昵称
					</view>
				</view>
				<view class="right">
					<view class="name">
						昵称
					</view>
					<view class="name">
						昵称
					</view>
				</view>
			</view>
			
			<view class="index-list2">
				如何用手帐改变你的一生？
			</view>
			
			<view class="index-list3">
				<image src="../../static/demo/datapic/3.jpg" 
				mode="widthFix" 
				lazy-load></image>
			</view>
			
			<view class="index-list4">
				<view class="left">
					<view class="name">
						昵称
					</view>
					<view class="name">
						昵称
					</view>
				</view>
				
				<view class="right">
					<view class="name">
						昵称
					</view>
					<view class="name">
						昵称
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.index-list {
		padding: 15upx;
		border-bottom: 1px solid lightgray;
		
		display: flex;
		flex-direction: column;
	}
	
	.index-list1 {
		display: flex;
		justify-content: space-between;
	}
	
	.index-list1>view:first-child {
		display: flex;
		align-items: center;
	}
	
	.index-list1>view:first-child>image {
		width: 50upx;
		height: 50upx;
		border-radius: 100%;
		margin-right: 10px;
	}
	
	.index-list1>view:last-child {
		display: flex;
		align-items: center;
	}
	
	.index-list1>view:last-child>view:first-child {
		margin-right: 10px;
	}
	
	.index-list3 {
		width: 100%;
		height: 200px;
	}
	
	.index-list3>image {
		width: 100%;
		border-radius: 20upx;
	}
	 
	.index-list4 {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}
	
	.index-list4>view:first-child {
		display: flex;
		align-items: center;
	}
	
	.index-list4>view:first-child>view:first-child {
		margin-right: 10px;
	}
	
	.index-list4>view:last-child {
		display: flex;
		align-items: center;
	}
	
	.index-list4>view:last-child>view:first-child{
		margin-right: 10px;
	}
	
</style>
