<template>
	<div class="navigate" :class="{show:navigateShow}">

	</div>
</template>

<script lang="ts">
	import Vue from 'vue'

	export default Vue.extend({
		data(){
			return {
				navigateShow:true,
			}
		}
	})
</script>

<style lang="scss" scoped>
.navigate{
	position: fixed;
	left: 0;
	top: 0;
	height: 100vh;
	width: 180px;
	background-color: #fff;
	box-shadow: 0 0 5px #888;
}
.show{
	left: -180px;
}
</style>