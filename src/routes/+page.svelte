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
	text="Takein.ai automates the time-consuming pre-sales process for U.S.-based freelance designers and marketers, turning client inquiries into professional proposals in minutes instead of hours. Our AI assistant handles client intake, generates custom proposals, and streamlines payment collection—helping freelancers reclaim 5-10 hours per client while boosting proposal close rates from 20-36% to industry-leading levels. We're transforming how creative professionals convert leads into paid projects by eliminating the administrative burden that keeps them from their best work."
/>

<Testimonials
	testimonials={[
		{
<<<<<<< HEAD
			name: "Maya Chen",
			position: "Freelance UX Designer",
			company: "Chen Design Studio",
			quote:
				"Takein.ai saved me 8 hours per client on proposal writing and follow-ups. My close rate jumped from 25% to 42% in just two months. Now I spend time designing instead of chasing leads.",
			image: "/generated/image-medium-wide-professional-headshot-of-may.webp"
		},
		{
			name: "Carlos Rodriguez",
			position: "Digital Marketing Consultant",
			company: "Rodriguez Media",
			quote:
				"Before Takein.ai, I was losing potential clients because my proposals took too long to send. Now I deliver professional proposals within hours, not days. Closed $45K in new business last quarter.",
			image: "/generated/image-medium-wide-professional-headshot-of-car.webp"
		},
		{
			name: "Priya Patel",
			position: "Brand Strategy Consultant",
			company: "Patel Creative",
			quote:
				"The AI handles all the tedious intake questionnaires and contract prep. I went from working 60-hour weeks to 45 hours while actually increasing revenue by 30%. Game changer for work-life balance.",
			image: "/generated/image-medium-wide-professional-headshot-of-pri.webp"
=======
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
>>>>>>> 09129f0b775b512eb1acd5f632b315dd45133fe6
		}
	]}
/>

<Features
<<<<<<< HEAD
	title="Why freelancers choose Takein"
	subtitle="Turn your expertise into paid projects faster with AI-powered automation that eliminates pre-sales busywork"
	features={[
		{
			title: "AI-powered client intake",
			description: "Smart forms gather everything you need to scope projects accurately. No more back-and-forth emails or discovery calls that go nowhere."
		},
		{
			title: "Instant proposal generation",
			description: "Generate professional, scoped proposals automatically as soon as clients complete intake. Review, edit, or auto-send with confidence."
		},
		{
			title: "Upfront payment collection",
			description: "Get paid before you start working with seamless payment processing. Never chase invoices or have awkward money conversations again."
		},
		{
			title: "Save 5-10 hours per client",
			description: "Eliminate manual pre-sales work that keeps you from doing what you love. Focus on delivering great work, not managing admin."
		},
		{
			title: "Double your close rates",
			description: "Professional intake flows and instant proposals help you close more deals. Freelancers report 2x higher proposal acceptance rates."
		},
		{
			title: "Brand-consistent experience",
			description: "Every client touchpoint matches your brand identity. Look professional from first contact to final payment."
=======
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
>>>>>>> 09129f0b775b512eb1acd5f632b315dd45133fe6
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
