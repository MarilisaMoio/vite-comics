<script>
	import AppHeader from "./components/AppHeader.vue"
	import AppCards from "./components/AppCards.vue"

	export default {
		components: {
			AppHeader,
			AppCards
		}
	}
</script>

<template>
	<AppHeader></AppHeader>
	<main>
		<appCards></appCards>
	</main>
</template>

<style lang="scss">
	@use "./style/generic";
</style>
