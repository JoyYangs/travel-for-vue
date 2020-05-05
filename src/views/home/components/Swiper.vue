<template>
	<div class="wrapper">
		<swiper ref="mySwiper" :options="swiperOptions">
			<swiper-slide v-for="item of swiperList" :key="item.id">
				<img class="swiper-img" :src="item.image">
			</swiper-slide>
			<div class="swiper-pagination" slot="pagination"></div>
		</swiper>
	</div>
</template>

<script>
export default {
	name: "HomeSwiper",
	data() {
		return {
			swiperOptions: {
				pagination: '.swiper-pagination',
				loop: true
			},
			swiperList: [{
				id: '0001',
				image: 'https://img1.qunarzz.com/qs/1912/50/067a6d82e1ca0b02.jpg'
			}, {
				id: '0002',
				image: 'https://img1.qunarzz.com/qs/2001/d9/8844a335554e1c02.jpg'
			},{
				id: '0003',
				image: 'https://imgs.qunarzz.com/douxing/i3/1612/71/9b6daaaf97b6fa02.jpg'
			}, {
				id: '0004',
				image: 'https://imgs.qunarzz.com/douxing/i3/1612/71/9b6daaaf97b6fa02.jpg'
			},{
				id: '0005',
				image: 'https://img1.qunarzz.com/qs/2001/d9/8844a335554e1c02.jpg'
			}, {
				id: '0006',
				image: 'https://imgs.qunarzz.com/douxing/i3/1612/71/9b6daaaf97b6fa02.jpg'
			}]
		}
	}
}
</script>

<style lang="stylus" scoped>
	wrapper >>> .swiper-pagination-bullet-active
		background  #ffffff
	.wrapper 
		overflow hidden
		width 100%
		height .100rem
		padding-bottom 31.25%
		.swiper-img 
			width 100%
			background-color red
</style>