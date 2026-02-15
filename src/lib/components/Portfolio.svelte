<script lang="ts">
	// Portfolio component
</script>

<section id="portfolio" class="w-full bg-white py-16 md:py-24">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-12 px-6 md:px-12 lg:grid-cols-12 lg:gap-20 lg:px-20">
		<!-- Left Column: Text -->
		<div class="lg:col-span-4 lg:pt-12">
			<h3 class="mb-6 text-2xl font-bold tracking-tight text-black">Investment Focus</h3>
			<p class="mb-8 text-lg leading-relaxed text-gray-900 md:text-xl">
				We focus on prime urban real estate within the Swiss Golden Triangle. From single high-end apartments to multi-family residential buildings, our portfolio represents stability and long-term value.
			</p>
			<div class="space-y-4 text-sm font-medium uppercase tracking-widest text-gray-500">
				<p>• Zurich City Center</p>
				<p>• Zug Premium Districts</p>
				<p>• Baden Urban Core</p>
			</div>
		</div>

		<!-- Right Column: Projects -->
		<div class="flex flex-col gap-8 lg:col-span-8">
			<!-- Project 1 -->
			<div class="relative aspect-[16/9] w-full overflow-hidden bg-gray-100">
				<img
					src="/generated/image-a-premium-high-end-apartment-building-in-1771116268031-0.webp"
					alt="Zurich City Center Property"
					class="h-full w-full object-cover transition-transform duration-700 hover:scale-105"
				/>
				<span class="absolute top-4 left-4 text-xs font-bold uppercase tracking-wider text-white bg-black/50 px-2 py-1">Zurich City</span>
			</div>

			<!-- Project 2 -->
			<div class="relative aspect-[16/9] w-full overflow-hidden bg-gray-100">
				<img
					src="/generated/image-a-modern-multi-family-residential-buildi-1771116270327-1.webp"
					alt="Zug Residential Building"
					class="h-full w-full object-cover transition-transform duration-700 hover:scale-105"
				/>
				<span class="absolute top-4 left-4 text-xs font-bold uppercase tracking-wider text-white bg-black/50 px-2 py-1">Zug Region</span>
			</div>

			<!-- Project 3 -->
			<div class="relative aspect-[16/9] w-full overflow-hidden bg-gray-100">
				<img
					src="/generated/image-a-classic-well-preserved-urban-residenti-1771116272673-2.webp"
					alt="Baden Urban Property"
					class="h-full w-full object-cover transition-transform duration-700 hover:scale-105"
				/>
				<span class="absolute top-4 left-4 text-xs font-bold uppercase tracking-wider text-white bg-black/50 px-2 py-1">Baden Center</span>
			</div>
		</div>
	</div>
</section>
