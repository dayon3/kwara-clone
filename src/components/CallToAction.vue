<template>
	<div>
		<div class="cta">
			<h1>
				Attract more members to your SACCO. Try Kwara risk free with our 2-week
				trail.
			</h1>
			<button class="btn">Let us call you</button>
		</div>
	</div>
</template>

<script>
export default {
	name: 'CallToAction',
};
</script>

<style scoped>
.cta {
	padding: 2rem;
	padding-bottom: 4rem;
	margin: 0 4rem;
	background-color: #f0f2f7;
	border-radius: 0.5rem;
}

h1 {
	font-size: 2rem;
}

@media only screen and (min-width: 768px) {
	h1 {
		font-size: 2.8rem;
	}
}
</style>
