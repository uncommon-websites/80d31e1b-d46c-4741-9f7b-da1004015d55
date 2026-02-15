<script lang="ts">
	// Strategy component
</script>

<section id="strategy" class="w-full bg-white py-16 md:py-24">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div>
			<h2 class="mb-8 text-4xl font-bold leading-tight tracking-tight text-black md:text-5xl lg:text-6xl">
				Discreet. Family-run.<br />
				Long-term.
			</h2>
			<p class="max-w-md text-lg leading-relaxed text-gray-800">
				VUE AG specializes in off-market real estate acquisitions, providing property owners with a professional, quiet, and fair exit strategy.
			</p>
		</div>

		<!-- Right Column: List -->
		<div class="flex flex-col">
			{#each [
				'Off-market exclusivity',
				'Golden Triangle focus',
				'Family-held capital',
				'Absolute confidentiality'
			] as item}
				<div class="group flex cursor-pointer items-center justify-between border-b border-gray-200 py-6 transition-colors hover:bg-gray-50">
					<span class="text-xl font-medium text-gray-900">{item}</span>
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-400 transition-transform group-hover:rotate-90 group-hover:text-black">
						<line x1="12" y1="5" x2="12" y2="19"></line>
						<line x1="5" y1="12" x2="19" y2="12"></line>
					</svg>
				</div>
			{/each}
		</div>
	</div>
</section>
