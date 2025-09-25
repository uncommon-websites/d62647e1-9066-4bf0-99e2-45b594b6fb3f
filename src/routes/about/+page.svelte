<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Craft over paperwork",
			description: "Every minute should be spent on creative work, not administrative busywork."
		},
		{
			title: "Technical depth",
			description: "Building production-grade systems that handle complexity behind simple interfaces."
		},
		{
			title: "Freelancer success",
			description: "Our wins are measured by the creative professionals who thrive using our platform."
		}
	];
</script>

<SecondaryHero
	title="From lead to paid in minutes"
	subtitle="No more quoting guesswork or admin drift"
	imageSrc="/generated/image-a-professional-freelancer-working-at-a-m.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"After years of building production payment rails and Lightning Network protocols, founder Andrew witnessed the same frustrating pattern everywhere: talented freelancers drowning in pre-sales admin work. Despite their creative brilliance, designers and marketers were losing 5-10 hours per client on intake forms, proposal writing, and payment setup—time that should have been spent doing what they love. With proposal close rates stuck at 20-36%, it was clear that administrative friction was killing creative potential.",
		"Drawing from his experience turning protocol-level complexity into user-ready systems at companies like Bitlum and ZigZag, Andrew saw an opportunity to apply the same principles to freelancer workflows. What if AI could handle the tedious parts—client intake, proposal generation, payment processing—while preserving the human creativity that makes each freelancer unique? Takein.ai was born from this vision: an intelligent assistant that transforms scattered admin tasks into a streamlined system, letting freelancers focus on craft over paperwork.",
		"Today, we're targeting the $1.27 trillion freelance market with a solution that doesn't just save time—it fundamentally changes how creative professionals run their businesses. By 2028, we envision 90 million users leveraging our AI to convert leads faster, close deals more effectively, and reclaim their creative energy. Every hour we save on admin is an hour returned to innovation, design, and the meaningful work that drives our economy forward."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet our founder."
	subtitle="From protocol engineer to freelancer advocate."
	stakeholders={[
		{
			name: "Andrew",
			position: "Founder",
			bio: "Core contributor to Lightning Network protocols (LND and BOLT specs), built production payment systems at Bitlum, and shipped Lightning-based DEX at ZigZag. Bringing protocol-level expertise to solve real freelancer problems.",
			image: "/generated/image-a-professional-software-engineer-working.webp"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Our mission."
	subtitle="Serving the 90M freelancers transforming the $1.27T market"
	stakeholders={[
		{
			name: "Targeting US Market",
			bio: "Starting with US-based freelancers who need streamlined project kickoffs",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Growing to 90M Users",
			bio: "Scaling intelligent automation to transform how creative professionals work",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "$1.27T Opportunity",
			bio: "Capturing value in the massive global freelance economy",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to reclaim your time?"
	subtitle="From lead to paid in minutes"
	description="Join the freelancers who've eliminated admin drift and increased their close rates with intelligent project kickoff automation."
/>
