<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconFileText from "~icons/lucide/file-text";
	import IconCreditCard from "~icons/lucide/credit-card";
	import IconBarChart3 from "~icons/lucide/bar-chart-3";
	import IconStar from "~icons/lucide/star";
	import IconShield from "~icons/lucide/shield";
</script>

<Hero
	title="Turn leads into paid projects faster"
	subtitle="Skip the admin. Send proposals. Get paid. Takein.ai's AI assistant streamlines client intake, proposal generation, and payment—saving freelancers 5-10 hours per client while boosting close rates."
	imageSrc="/generated/image-a-confident-freelance-designer-working-e.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/squarespace.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mailchimp.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/canva.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Rodriguez",
			position: "Brand Designer",
			company: "Independent Studio",
			quote:
				"Takein.ai cut my proposal time from 6 hours to 45 minutes. I went from closing 2 out of 10 leads to 7 out of 10. That's an extra $15k in monthly revenue just from better proposals.",
			image: "/generated/image-professional-headshot-of-a-confident-fem.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Marketing Consultant",
			company: "Freelance",
			quote:
				"The AI assistant handles all my intake calls and generates detailed project briefs automatically. I save 8 hours per week on admin work, which means I can take on two more clients monthly.",
			image: "/generated/image-professional-headshot-of-a-male-marketin.webp"
		},
		{
			name: "Zara Chen",
			position: "Web Designer",
			company: "Digital Freelancer",
			quote:
				"My biggest pain was losing qualified leads to slow follow-ups. Now clients get professional proposals within 2 hours of our first call. My close rate jumped from 25% to 42% in three months.",
			image: "/generated/image-professional-headshot-of-a-young-female-.webp"
		}
	]}
/>

<Features
	title="Turn leads into paid projects. Fast."
	subtitle="Stop losing clients before the work even starts. Save 5-10 hours per client while doubling your close rates."
	features={[
		{
			title: "AI-powered client intake",
			description: "Smart forms extract project requirements from messy client briefs automatically. No more back-and-forth emails or missed details.",
			icon: IconBrain
		},
		{
			title: "Instant proposal generation",
			description: "Create tailored, professional proposals in minutes, not hours. Review, edit, or auto-send when everything looks perfect.",
			icon: IconFileText
		},
		{
			title: "Upfront payment collection",
			description: "Get paid before projects start with seamless payment processing. No more late payments or awkward money conversations.",
			icon: IconCreditCard
		},
		{
			title: "Lead conversion analytics",
			description: "Track and optimize your close rates with actionable insights. See what's working and double down on success.",
			icon: IconBarChart3
		},
		{
			title: "Branded client experience",
			description: "Every touchpoint matches your brand for a professional experience that builds trust and commands premium rates.",
			icon: IconStar
		},
		{
			title: "Project scope protection",
			description: "AI monitors for scope creep and suggests contract adjustments to protect your time and maintain profitability.",
			icon: IconShield
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
