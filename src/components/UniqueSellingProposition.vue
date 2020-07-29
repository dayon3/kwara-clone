<template>
	<div class="usp wrapper">
		<div class="headerContent">
			<div class="headerContent__content">
				<h2 class="title">Why Kwara</h2>
				<p>
					Kwara helps SACCOs thrive by unlocking their full digital potential.
				</p>
			</div>
		</div>
		<div class="usp__item--list">
			<div class="usp__item">
				<div class="usp__item--container">
					<picture class="usp__item--icon">
						<source media="(min-width: )" srcset="" />
						<img src="../assets/icons/zap.svg" alt="zap" />
					</picture>
					<h3>Online member signup</h3>
				</div>
				<div class="usp-item--paragraphContainer">
					<p>
						Get more members, faster. Future members can register from wherever
						they are, in minutes, compliantly. No paperwork required.
					</p>
				</div>
			</div>
			<div class="usp__item">
				<div class="usp__item--container">
					<picture class="usp__item--icon">
						<source media="(min-width: )" srcset="" />
						<img src="../assets/icons/gauge.svg" alt="gauge" />
					</picture>
					<h3>Consistent and human support</h3>
				</div>
				<div class="usp-item--paragraphContainer">
					<p>
						Free and reliable support when you need it. Rely on Kwara's support
						for your peace of mind.
					</p>
				</div>
			</div>
			<div class="usp__item">
				<div class="usp__item--container">
					<picture class="usp__item--icon">
						<source media="(min-width: )" srcset="" />
						<img src="../assets/icons/lock.svg" alt="lock" />
					</picture>
					<h3>Military-grade security</h3>
				</div>
				<div class="usp-item--paragraphContainer">
					<p>
						The security of your SACCO is assured. Find everything intact on
						Monday morning.
					</p>
				</div>
			</div>
			<div class="usp__item">
				<div class="usp__item--container">
					<picture class="usp__item--icon">
						<source media="(min-width: )" srcset="" />
						<img src="../assets/icons/check-badge.svg" alt="check-badge" />
					</picture>
					<h3>No CAPEX. Pay as you go.</h3>
				</div>
				<div class="usp-item--paragraphContainer">
					<p>
						Spend less upfront and less over time. Save money to deliver more
						dividends to your members.
					</p>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'UniqueSellingProposition',
};
</script>

<style scoped>
.wrapper {
	padding: 2rem;
	max-width: 1200px;
	margin: auto 20px;
}
.usp {
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
	justify-content: space-between;
}
.title {
	font-size: 2.4rem;
	color: rgb(32, 44, 44);
	margin-bottom: 8px;
	font-weight: 700;
	line-height: 140%;
}
p {
	font-size: 1.25rem;
	line-height: 140%;
	color: rgba(32, 44, 44, 0.7);
	margin-bottom: 32px;
	text-align: left;
}
picture {
	display: block;
	text-align: center;
}

.usp > .headerContent {
	margin-bottom: 48px;
}

.headerContent__content > p {
	text-align: center;
}

.usp__item {
	display: flex;
	flex-direction: column;
	align-items: flex-start;
	border-bottom: 1px solid rgb(239, 239, 239);
}

.usp__item--container {
	display: flex;
	align-items: center;
	width: 100%;
	padding: 16px 0px;
	flex: 1 0 90px;
}

.usp__item--icon {
	margin-right: 8px;
}

.usp__item--paragraphContainer {
	padding: 0px 16px;
}

@media only screen and (min-width: 768px) {
	.wrapper {
		max-width: calc(100% - 40px);
	}

	p {
		font-size: 0.9rem;
		line-height: 150%;
	}

	.usp {
		text-align: left;
	}

	.usp > .headerContent {
		margin-bottom: 80px;
		text-align: center;
	}

	.usp__item--list {
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
	}

	.usp__item {
		margin-bottom: 54px;
		flex: 0 0 calc((100% - 62px) / 2);
		border-bottom: 0px;
	}

	.usp__item--container {
		flex-direction: column;
		align-items: flex-start;
		padding: 0px;
		flex: 1 1 0%;
	}

	.usp__item--paragraphContainer {
		padding: 0px;
		margin-top: 8px;
	}
}

@media only screen and (min-width: 1024px) {
	.headerContent {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.headerContent__content {
		max-width: calc(569px);
		text-align: left;
	}
}
</style>
