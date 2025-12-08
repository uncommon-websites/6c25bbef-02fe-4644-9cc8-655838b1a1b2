<script lang="ts">
	import Navbar from '$lib/Navbar.svelte';
	import Hero from '$lib/Hero.svelte';
	import Features from '$lib/Features.svelte';
	import CTA from '$lib/CTA.svelte';
	import DataModel from '$lib/DataModel.svelte';
	import Testimonials from '$lib/Testimonials.svelte';
	import BuildFast from '$lib/BuildFast.svelte';
	import Stats from '$lib/Stats.svelte';
	import Security from '$lib/Security.svelte';
	import FooterCTA from '$lib/FooterCTA.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<Navbar />
<main class="bg-white min-h-screen">
	<Hero />
	<Features />
	<CTA />
	<DataModel />
	<Testimonials />
	<BuildFast />
	<Stats />
	<Security />
	<FooterCTA />
</main>
<Footer />

