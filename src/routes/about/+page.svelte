<script lang="ts">
	import { resolve } from '$app/paths';
	import ArrowLeftIcon from '@lucide/svelte/icons/arrow-left';
</script>

<svelte:head>
	<title>About – Take Shelter Now</title>
	<meta name="description" content="About Take Shelter Now – helping people in the Springfield, MO region find nearby emergency shelters quickly." />
</svelte:head>

<div class="mx-auto max-w-2xl px-6 py-10">
	<a
		href={resolve('/')}
		class="text-text-secondary hover:text-text-primary mb-6 inline-flex items-center gap-1.5 text-sm transition-colors"
	>
		<ArrowLeftIcon class="size-4" />
		Back to shelters
	</a>

	<h1 class="mb-6 text-2xl font-bold">About Take Shelter Now</h1>

	<p class="text-text-secondary mb-4 text-sm leading-relaxed">
		Take Shelter Now is a free tool that helps people in the Springfield, MO region quickly find
		nearby emergency weather shelters. When severe weather strikes, every second counts — this site
		is designed to get you to safety as fast as possible.
	</p>

	<p class="text-text-secondary mb-4 text-sm leading-relaxed">
		This project is built and maintained by
		<a
			href="https://www.opensgf.org/"
			class="text-[#0892d2] underline hover:text-[#0780bc]"
			target="_blank"
			rel="noopener noreferrer"
		>
			Open SGF
		</a>, a volunteer civic-tech organization in Springfield, MO.
	</p>

	<p class="text-text-secondary mb-4 text-sm leading-relaxed">
		Shelter information is sourced from a curated, community-maintained list and is updated
		regularly. Only verified, currently open shelters are shown.
	</p>

	<h2 class="mb-3 mt-8 text-base font-semibold">How it works</h2>
	<ul class="text-text-secondary mb-4 list-inside list-disc space-y-1 text-sm">
		<li>Share your location or enter an address</li>
		<li>See nearby shelters sorted by distance</li>
		<li>Filter by accessibility, pets, power, and more</li>
		<li>Get directions with your preferred maps app</li>
	</ul>

	<h2 class="mb-3 mt-8 text-base font-semibold">Submit a shelter</h2>
	<p class="text-text-secondary mb-2 text-sm leading-relaxed">
		Know of a shelter that should be listed? Send us the details and we'll review it for inclusion.
	</p>
	<a
		href="mailto:example@email.com"
		class="inline-flex items-center gap-1.5 text-sm text-[#0892d2] underline hover:text-[#0780bc]"
	>
		example@email.com
	</a>

	<h2 class="mb-3 mt-8 text-base font-semibold">Frequently asked questions</h2>
	<div class="space-y-5">
		<div>
			<p class="mb-1 text-sm font-medium">Is this service free?</p>
			<p class="text-text-secondary text-sm leading-relaxed">
				Yes. Take Shelter Now is completely free to use and always will be.
			</p>
		</div>
		<div>
			<p class="mb-1 text-sm font-medium">How current is the shelter data?</p>
			<p class="text-text-secondary text-sm leading-relaxed">
				Shelter information is pulled from a community-maintained list and updated regularly. Only
				shelters with a verified "open" status are shown.
			</p>
		</div>
		<div>
			<p class="mb-1 text-sm font-medium">What area does this cover?</p>
			<p class="text-text-secondary text-sm leading-relaxed">
				Currently the Springfield, MO region. We hope to expand coverage over time with community
				help.
			</p>
		</div>
		<div>
			<p class="mb-1 text-sm font-medium">Does the site store my location?</p>
			<p class="text-text-secondary text-sm leading-relaxed">
				Your location is saved only in your browser's local storage so it persists between visits. It
				is never sent to our servers.
			</p>
		</div>
		<div>
			<p class="mb-1 text-sm font-medium">How do I contribute to the project?</p>
			<p class="text-text-secondary text-sm leading-relaxed">
				This is an open-source project. Visit us on
				<a
					href="https://github.com/Open-SGF/take-shelter-now"
					class="text-[#0892d2] underline hover:text-[#0780bc]"
					target="_blank"
					rel="noopener noreferrer"
				>
					GitHub
				</a>
				to report issues or submit pull requests.
			</p>
		</div>
	</div>
</div>
