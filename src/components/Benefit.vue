<template>
	<div>
		<ul>
			<li v-for="benefit in saccoBenefits" :key="benefit.message">
				<img
					src="../assets/icons/check_bullet_green.svg"
					alt="check bullet icon"
				/>
				<p>{{ benefit.message }}</p>
			</li>
		</ul>
	</div>
</template>

<script>
export default {
	name: 'Benefit',
	/* TODO: refactor: state */
	data() {
		return {
			saccoBenefits: [
				{ message: 'Empower member to transact from anywhere' },
				{ message: 'Reduce repeat manual work' },
				{ message: 'Enjoy reliability with free + consistent support' },
				{ message: 'Manage all operations yourself, end to end' },
				{ message: 'Reduce your reliance on vendors' },
				{ message: 'Benefit from a SACCO-specific platform' },
			],
			memberBenefits: [
				{ message: 'Less cost for your SACCO means higher dividend for you' },
				{ message: 'Faster loan processing with less paperwork required' },
				{ message: "Easily know how much you've saved and how much you owe" },
				{ message: 'Quickly register for a SACCO online from anywhere' },
				{
					message:
						'Build your credit score you can borrow more. Goodbye shylocks',
				},
			],
		};
	},
};
</script>

<style scoped>
p {
	/* TODO: refactor */
	color: rgba(32, 44, 44, 0.7);
	margin-left: 1rem;
}

ul {
	padding: 0;
}

li {
	display: flex;
}
</style>
