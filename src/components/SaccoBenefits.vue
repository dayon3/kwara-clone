<template>
	<div>
		<div class="container">
			<div class="heading">
				<h2>
					The first shared digital banking<br />
					platform with a cooperative spirit
				</h2>
			</div>
			<div class="product">
				<div class="product-benefits">
					<h3>Benefits for SACCOs</h3>
					<p>
						Take your SACCO to the next level. Achieve your<br />
						ICT strategy and easily go digital.
					</p>
					<Benefit />
					<button class="btn">More about kwara for SACCOs</button>
				</div>
				<div class="product-img">
					<img
						src="../assets/kwara-product-web-members@2x.png"
						alt="Kwara product web members"
					/>
				</div>
			</div>
		</div>
		<div class="container">
			<div class="product">
				<div class="product-img">
					<img
						src="../assets/kwara-loans-mobile-02.png"
						alt="Kwara product web members"
					/>
				</div>

				<div class="product-benefits">
					<h3>Benefits for Members</h3>
					<p>
						Benefit from clarity on your financial status, to <br />
						understand how your SACCO is growing your <br />
						wealth.
					</p>
					<Benefit />
					<button class="btn">More about kwara for Members</button>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
import Benefit from '../components/Benefit';

export default {
	name: 'SaccoBenefits',
	components: {
		Benefit,
	},
};
</script>

<style scoped>
.container {
	padding: 2rem;
	padding-bottom: 4rem;
}
.heading {
	padding: 1.5rem 0;
}
h2 {
	font-size: 2.4rem;
}
h3 {
	font-size: 2.1rem;
	margin: 0.5rem 0;
}
p {
	/* TODO: refactor */
	color: rgba(32, 44, 44, 0.7);
	font-size: 1.25rem;
	margin: 0.3rem 0;
}
.product {
	display: flex;
}

.product > div {
	width: 50%;
	padding: 1rem;
}

.product-benefits {
	display: flex;
	flex-direction: column;
	align-items: flex-start;
	margin-right: 1.5rem;
	text-align: left;
}

.product-img {
	flex-basis: 50%;
}

.product-img img {
	width: 100%;
}
</style>
