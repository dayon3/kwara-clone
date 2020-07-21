<template>
	<div class="navbar-wrapper">
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
				</ul>
				<button class="btn">Sign Up</button>
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
.navbar-wrapper {
	position: fixed;
	top: 20px;
	left: 0;
	right: 0;
	background: rgba(255, 255, 255, 0.9);
	border: 1px solid rgba(0, 0, 0, 0.08);
	border-radius: 8px;
	box-shadow: 0px 6px 8px rgba(0, 0, 0, 0.04);
	margin: 0 30px;
}
.nav {
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 8px 18px;
}
.nav-links {
	display: flex;
	align-items: center;
}
ul {
	list-style-type: none;
	padding: 0;
	margin-right: 20px;
}
li {
	display: inline-block;
	margin: 0 16px;
}
a {
	color: #202c2c;
	text-decoration: none;
	font-size: 0.95rem;
}
</style>
