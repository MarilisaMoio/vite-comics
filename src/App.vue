<script>
	import AppHeader from "./components/AppHeader.vue"
	import AppCards from "./components/AppCards.vue"
	import AppIcons from "./components/AppIcons.vue"

	export default {
		components: {
			AppHeader,
			AppCards,
			AppIcons
		}
	}
</script>

<template>
	<AppHeader></AppHeader>
	<main>
		<AppCards></AppCards>
		<AppIcons></AppIcons>
	</main>
</template>

<style lang="scss">
	@use "./style/generic";
</style>
