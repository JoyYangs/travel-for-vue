<template>
	<div class="header">
		<div class="header-left">
			<span class="iconfont">&#xe6bc;</span>
		</div>
		<div class="header-input">输入城市/景点/游玩主题</div>
		<div class="header-right">城市</div>
	</div>
</template>

<script>
	export default {
		name: "Header"
	}
</script>

<style lang="stylus" scoped>
	@import '~@/assets/css/variable.styl'
	.header
		display flex
		height .86rem
		line-height .86rem
		text-align center
		background-color $bgColor
		.header-left
			width .64rem
			float left
		.header-input 
			flex 1
			margin-left .1rem
			color #cccccc
			background #ffffff
			border-radius .1rem
			margin-top .12rem
			height .62rem
			line-height .62rem
			text-align left 
			padding-left .1rem
		.header-right
			width 1.24rem
			float right


</style>