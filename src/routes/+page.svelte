<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Hire for values. Not just resumes."
	subtitle="Show your culture. Attract better talent."
	imageSrc="/generated/image-a-professional-startup-office-in-a-nordi.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/spotify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/klarna.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Attract culture-aligned talent"
	subtitle="Transform your invisible team culture into a magnetic talent attractor"
	features={[
		{
			title: "AI culture discovery",
			description:
				"Lucy AI automatically captures your team's principles, rituals, and values from everyday interactions. No surveys or manual input required."
		},
		{
			title: "Smart candidate pre-qualification",
			description:
				"Stop wasting weeks screening misaligned candidates. Our AI matches culture profiles before you even meet them."
		},
		{
			title: "Culture-to-talent matching",
			description:
				"Transform your invisible culture into searchable profiles that attract candidates who thrive in your exact environment."
		},
		{
			title: "Automated culture profiling",
			description:
				"Scale culture-based hiring without manual work. Our system continuously updates your culture profile as your team evolves."
		},
		{
			title: "Senior talent magnetism",
			description:
				"Attract experienced professionals who value culture fit over just compensation. Perfect for competitive Stockholm tech market."
		},
		{
			title: "Recruiter-free hiring",
			description:
				"Skip expensive recruiters and attract pre-qualified, culture-aligned candidates directly to your opportunities."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
