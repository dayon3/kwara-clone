<template>
	<div class="container">
		<header>
			<div class="details">
				<h1>The digital banking platform for SACCOs</h1>
				<p>
					Embrace digital transformation. Gain control over daily operations,
					attract more members, and increase revenues.
				</p>
				<button class="btn">Let us call you</button>
				<div class="clients">
					<span>Trusted by over 10 SACCOs and 27,000 members</span>
					<div class="clients-logos">
						<img
							src="../assets/kenya-bankers-sacco-kwara-logo-grey.png"
							alt="Kenya bankers sacco logo"
						/>
						<img
							src="../assets/ollin-sacco-kwara-logo-grey.png"
							alt="Ollin sacco logo"
						/>
						<img
							src="../assets/aak-sacco-kwara-logo-grey.png"
							alt="AAK sacco logo"
						/>
					</div>
				</div>
			</div>
			<div class="hero">
				<img src="../assets/kwara-loans-mobile.png" alt="kwara loans mobile" />
			</div>
		</header>
	</div>
</template>

<script>
export default {
	name: 'Header',
};
</script>

<style scoped>
.container {
	background-color: #faf0f0;
	min-height: 664px;
	min-width: 100vw;
	padding-top: 100px;
	display: flex;
}
header {
	text-align: left;
	display: flex;
	width: 1200px;
	min-width: 100%;
	margin: 0 50px;
}
h1 {
	font-size: 48px;
	letter-spacing: 2px;
	line-height: 1.4;
	margin-bottom: 0.5rem;
}
p {
	font-size: 1.4rem;
	margin-bottom: 1.5rem;
	margin-top: 0;
	color: rgba(32, 44, 44, 0.7);
}
.clients {
	border-top: 1px solid rgba(0, 0, 0, 0.04);
	border-bottom: 1px solid rgba(0, 0, 0, 0.04);
	margin-top: 2.8rem;
	padding: 1rem 0 1.2rem;
}
.hero img {
	height: 664px;
}
</style>
