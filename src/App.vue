<template>
	<div id="app">
		<NavBar />
		<Header />
		<main>
			<SaccoBenefits />
			<CallToAction />
		</main>
	</div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Header from './components/Header.vue';
import SaccoBenefits from './components/SaccoBenefits.vue';
import CallToAction from './components/CallToAction.vue';

export default {
	name: 'App',
	components: {
		NavBar,
		Header,
		SaccoBenefits,
		CallToAction,
	},
};
</script>

<style>
@font-face {
	font-family: 'Brown';
	src: url('assets/fonts/lineto-brown-regularalt.woff2');
}

body {
	font-family: 'Brown', sans-serif;
	margin: 0;
	overflow-x: hidden;
	background-color: #faf0f0;
	height: 664px;
}

/* adjust width */
body::-webkit-scrollbar {
	width: 6px;
}

/* change track background */
body::-webkit-scrollbar-track {
	background: #202c2c;
}

/* change thumb background */
body::-webkit-scrollbar-thumb {
	background: #3a68c0;
}

.btn {
	background: rgb(58, 104, 192);
	border: none;
	border-radius: 50px;
	color: #fff;
	padding: 12px 24px;
	font-size: 16px;
	transition: background 0.3s ease-out;
}
.btn:hover {
	background: rgba(58, 104, 192, 0.88);
}
.btn:focus {
	outline: none;
}
</style>

<style lang="css" scoped>
#app {
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #202c2c;
	max-width: 100%;
	width: 1280px;
	margin: 0 auto;
}

main {
	background-color: #fff;
	border-radius: 0.5rem;
	z-index: 999;
	margin-bottom: 3rem;
	padding-bottom: 4rem;
}
</style>
