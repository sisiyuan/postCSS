<style src="../../assets/css/global.css"></style>
<style module>
	.app-header[data-role="app-header"]{
		& .title{
			color: #00f;
		}
	}
</style>

<template>
	<div id="app">
		<app-header :class="$style['app-header']"></app-header>
	</div>
</template>

<script>
import header from './components/header/header'
export default {
	name: 'app',
	components: {
		"app-header": header
	}
}
</script>