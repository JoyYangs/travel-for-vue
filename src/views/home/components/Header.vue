<template>
	<div class="header">
		<div class="header-left">
			<span class="iconfont">&#xe6bc;</span>
		</div>
		<div class="header-input">输入城市/景点/游玩主题</div>
		<router-link to="/city">
			<div class="header-right">城市</div>
		</router-link>
		
	</div>
</template>

<script>
export default {
	name: "HomeHeader"
}
</script>

<style scoped>
	.header {
		display: flex;
		height: 43px;
		line-height: 43px;
		text-align: center;
		background-color: #00bcd4;
	}

	.header-left {
		width: 32px;
		float: left;
	}

	.header-input {
		flex: 1;
		margin-top: 6px;
		margin-left: 5px;
		padding-left: 5px;
		border-radius: 5px;
		height: 32px;
		line-height: 32px;
		font-size: 13px;
		color: #cccccc;
		background-color: #ffffff;
	}

	.header-right {
		width: 62px;
		float: right;
	}
</style>