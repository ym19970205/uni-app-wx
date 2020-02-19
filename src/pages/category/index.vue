<template>
  <view class="category">
      <!-- 搜索组件 -->
    <search />
  </view>

</template>

<script>
	//1.导入搜索组件
import {search} from "@/cpts/search.vue"
export default {
    data(){

    },
    //2.注册搜索组件
	components:{
		search
	}
}
</script>

<style lang="less">

</style>