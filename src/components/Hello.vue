<template>
	<div>
		<p>{{ greeting }} world...</p>
	</div>
</template>

<script>
module.exports = {
	props: ['greeting']
}
</script>

<style scoped lang="scss">
@import "../scss/variables.scss";
p {
	color: $primary-color;
}
</style>