<script>
	import About from "./components/About.svelte";
	import Footer from "./components/Footer.svelte";
	import Hero from "./components/Hero.svelte";
	import Navbar from "./components/Navbar.svelte"; 
	import Projects from "./components/Projects.svelte";
	import Technologies from "./components/Technologies.svelte";
</script>

<!-- min-h-screen w-screen flex items-center flex-col pb-16 px-16 -->

<main>
	<Navbar />
	<Hero />
    <div class="break"><p>a</p></div>
	<Projects />
    <div class="break"><p>a</p></div>
	<Technologies />
	<About />
	<Footer />
</main>
<style>
	main{
		max-width: 1280px;
		width: 100%;
		margin: auto;	
	}
</style>