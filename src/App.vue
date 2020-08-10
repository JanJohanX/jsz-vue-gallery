<template>
	<div id="app">
		<jsz-vue-gallery v-bind:jsz-gallery="gallery"></jsz-vue-gallery>
	</div>
</template>

<script>

import JszVueGallery from 'jsz-vue-gallery';

export default {
	name: 'App',
	components: {
		JszVueGallery
	},
	data() {
		return {
			gallery: {
					"img1": {
						"imageSrc": '../images/img1.jpg',
					},
					"img2": {
						"imageSrc": '../images/img2.jpg',
					},
					"img3": {
						"imageSrc": '../images/img1.jpg',
					},
					"img4": {
						"imageSrc": '../images/img2.jpg',
					},
					"img5": {
						"imageSrc": '../images/img1.jpg',
					},
					"img6": {
						"imageSrc": '../images/img2.jpg',
					},
				}
		};
	}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
