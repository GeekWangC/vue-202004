<template>
	<div class="panel">
		{{context}}
	</div>
</template>
<script>
export default {
	name:'panel',
	props: {
    context: String,
  },
};
</script>

<style scoped>
	.panel{
		width: 100%;height: 100%;
		background: #f00;
		color: #fff;
	}
</style>