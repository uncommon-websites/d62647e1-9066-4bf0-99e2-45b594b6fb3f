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
		}
	]}
/>

<Features
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
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
