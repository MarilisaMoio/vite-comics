<script>
	import AppHeader from "./components/AppHeader.vue"
	import AppCards from "./components/AppCards.vue"
	import AppIcons from "./components/AppIcons.vue"
	import AppNav from "./components/AppNav.vue"

	export default {
		components: {
			AppHeader,
			AppCards,
			AppIcons,
			AppNav
		}
	}
</script>

<template>
	<AppHeader></AppHeader>
	<main>
		<AppCards></AppCards>
		<AppIcons></AppIcons>
	</main>
	<footer>
		<AppNav></AppNav>
	</footer>
</template>

<style lang="scss">
	@use "./style/generic";
</style>
