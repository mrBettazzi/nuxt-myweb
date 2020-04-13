<template>
	<section class="ambs">
		<Amb
			thumbnail="https://www.drivespark.com/img/2017/12/19-1513667806-vintage-cars-exempted-from-ban-ngt-india-5.jpg"
			title="Delicious Pizza"
			previewText="Awesome Pizza!" />
		<Amb
			thumbnail="https://www.drivespark.com/img/2017/12/19-1513667814-vintage-cars-exempted-from-ban-ngt-india-6.jpg"
			title="Delicious Salad"
			previewText="Awesome Salad!" />
	</section>
</template>

<script>
import Amb from '@/components/Amb';

export default {
	components: {
		Amb
	}
}
</script>

<style scoped>
.ambs {
	display: flex;
	flex-flow: row wrap;
	justify-content: left;
	align-items: center;
}
</style>