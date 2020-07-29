<template>
	<div id="app">
		<NavBar />
		<Header />
		<main>
			<Benefits />
			<CallToAction />
			<UniqueSellingProposition />
		</main>
	</div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Header from './components/Header.vue';
import Benefits from './components/Benefits.vue';
import CallToAction from './components/CallToAction.vue';
import UniqueSellingProposition from './components/UniqueSellingProposition.vue';

export default {
	name: 'App',
	components: {
		NavBar,
		Header,
		Benefits,
		CallToAction,
		UniqueSellingProposition,
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
	/* overscroll-behavior: none; */
	background-color: #faf0f0;
	height: 664px;
}

/* adjust width */
body::-webkit-scrollbar {
	width: 5px;
}

/* change track background */
body::-webkit-scrollbar-track {
	background: #202c2c;
	border-radius: 10rem;
}

/* change thumb background */
body::-webkit-scrollbar-thumb {
	background: #3a68c0;
	border-radius: 10rem;
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
	max-width: 1200px;
	margin: 0 auto;
	overflow-x: hidden;
}

main {
	background-color: #fff;
	border-radius: 0.5rem;
	margin-bottom: 3rem;
	padding-bottom: 4rem;
}
</style>
