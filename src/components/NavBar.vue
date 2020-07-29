<template>
	<div>
		<nav class="nav">
			<div class="nav-logo">
				<img src="../assets/kwara.svg" alt="kwara logo" />
			</div>
			<div class="nav-links">
				<ul>
					<li><a href="#">Pronto</a></li>
					<li><a href="#">For SACCOs</a></li>
					<li><a href="#">For Members</a></li>
					<li><a href="#">Security</a></li>
					<li><a href="#">Pricing</a></li>
					<li><a href="#">About</a></li>
					<li><a href="#">Blog</a></li>
					<li><a href="#">Sign in</a></li>
					<li>
						<button class="btn">Sign Up</button>
					</li>
				</ul>
			</div>
		</nav>
	</div>
</template>

<script>
export default {
	name: 'NavBar',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav {
	position: fixed;
	top: 20px;
	left: 50%;
	transform: translateX(-50%);
	z-index: 10;
	max-width: calc(100% - 40px + 8px);
	width: 1280px;
	height: 68px;
	background: rgba(255, 255, 255, 0.9);
	backdrop-filter: blur(4px);
	border: 1px solid rgba(0, 0, 0, 0.08);
	border-radius: 8px;
	box-shadow: 0px 6px 8px rgba(0, 0, 0, 0.04);
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 0px 20px;
}
.nav-links {
	align-items: center;
	display: none;
}
ul {
	list-style-type: none;
	padding: 0px;
}
li {
	display: inline-block;
	margin: 0px 16px;
}
li:last-child {
	margin: 0px;
}
a {
	color: #202c2c;
	text-decoration: none;
	font-size: 0.95rem;
}

@media only screen and (min-width: 1280px) {
	.nav {
		max-width: calc(1280px);
	}
}

@media only screen and (min-width: 1024px) {
	.nav {
		max-width: calc(100% - 50px);
	}

	.nav-links {
		display: flex;
	}
}
</style>
