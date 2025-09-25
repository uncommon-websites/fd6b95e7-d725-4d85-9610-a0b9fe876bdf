<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Culture-first thinking",
			description: "We believe every hire should strengthen your team's DNA, not just fill a role."
		},
		{
			title: "AI-powered precision",
			description: "Lucy AI helps us discover the invisible patterns that make teams truly click."
		},
		{
			title: "Values-based matching",
			description: "We match people based on shared principles, not just skills on paper."
		},
		{
			title: "Stockholm startup spirit",
			description: "Born from the Nordic mindset of innovation, collaboration, and sustainable growth."
		}
	];
</script>

<SecondaryHero
	title="Culture you can actually hire for"
	subtitle="Values-backed teams start here"
	imageSrc="/generated/image-a-modern-stockholm-startup-team-of-3-4-p.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and Investor sections removed - no actual team or investor information available for Team Vibe -->

<!-- CTA Section -->
<CallToAction
	title="Ready to attract the right talent?"
	subtitle="Transform your culture into your competitive advantage"
	description="Stop wasting weeks on culturally misaligned candidates. Join Stockholm's leading startups who use Team Vibe to attract senior talent without expensive recruiters. Let Lucy AI turn your team's invisible culture into your strongest hiring tool."
	imageSrc="/generated/image-a-confident-vp-of-people-in-a-stockholm-.webp"
/>
