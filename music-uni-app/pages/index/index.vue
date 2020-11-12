<template>
	<view class="content">
		<myAudio></myAudio>
	</view>
</template>

<script>
	import myAudio from "../../components/myaudio.vue"
	export default {
		data() {
			return {
			}
		},
		components:{
			myAudio
		},
		onLoad() {
		},
		methods: {
		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
