<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import Nav from "./components/nav.vue";
import Footer from "./components/footer.vue";
import Button from "./components/button.vue";
</script>

<template>
	<div class="min-h-screen flex flex-col">
		<div class="flex flex-col h-full">
			<header>
				<Nav />
			</header>
		</div>
		<main class="flex-grow">
			<div class="text-3xl text-lime-500">COucou</div>
			<div>
				<Button> Cliquez ici </Button>
			</div>
		</main>
		<Footer />
	</div>
</template>
