<template>
	<div class="flex mx-4 my-2 text-gray-900">
		<p><slot name="start">-</slot></p>
		<p class="ml-2 break-all">
			<slot></slot>
		</p>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>