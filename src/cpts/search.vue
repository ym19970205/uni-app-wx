<template>
  	<!-- 搜索框 -->
		<view class="search">
			<view class="search_box">
				<!-- 搜索栏 -->
			<input type="text">
				<!--取消按钮  -->
			</view> 
		</view>
</template>

<script>
export default {
    data(){
        return{
            
        }
    }

}
</script>

<style lang="less">
 //搜索区
		.search{
			background-color: #ff2d4a;
			box-sizing: border-box;
			padding: 20rpx 16rpx;
			.search_box{
				//搜索区
				input{
				height: 60rpx;
				width: 100%;
				background-color: #fff;
				border-radius: 5rpx;
			}
			}
		
		}
</style>