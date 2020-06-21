<template>
	<div class="swiper">
		我是轮播图位置
		<!-- <swiper ref="mySwiper" :options="swiperOptions">
			<swiper-slide>Slide 1</swiper-slide>
			<swiper-slide>Slide 2</swiper-slide>
			<swiper-slide>Slide 3</swiper-slide>
			<swiper-slide>Slide 4</swiper-slide>
			<swiper-slide>Slide 5</swiper-slide>
			<div class="swiper-pagination" slot="pagination"></div>
  	</swiper> -->
	</div>
</template>

<script>
// import { Swiper, SwiperSlide } from 'vue-awesome-swiper'

export default {
	name: "HomeSwiper",
	// components: {
	// 	Swiper,
	// 	SwiperSlide
	// },
	data() {
		return {
			// swiperOptions: {
			// 	pagination: {
			// 		el: '.swiper-pagination'
			// 	}
			// }
		}
	}
}
</script>

<style>
.swiper {
  height: 180px;
  width: 100%;
	background-color: aliceblue;
}

.swiper-slide {
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
	font-weight: bold;
	font-size: 20px;
	background-color: #ffffff;
}
</style>