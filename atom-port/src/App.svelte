<script>
	import About from "./components/About.svelte";
import Footer from "./components/Footer.svelte";
	import Hero from "./components/Hero.svelte";
	import Navbar from "./components/Navbar.svelte"; 
	import Projects from "./components/Projects.svelte";
	import Technologies from "./components/Technologies.svelte";
</script>

<main class="min-h-screen w-screen flex items-center flex-col pb-16">
	<Navbar />
	<Hero />
	<Projects />
	<Technologies />
	<About />
	<Footer />
</main>