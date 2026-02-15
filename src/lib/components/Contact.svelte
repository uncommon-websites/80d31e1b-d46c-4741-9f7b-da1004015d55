<script lang="ts">
	// Contact component
</script>

<section class="w-full bg-white py-16 md:py-24" id="contact">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div class="flex flex-col justify-between">
			<div>
				<h2 class="mb-8 text-3xl font-bold leading-tight tracking-tight text-black md:text-4xl">
					Inquire Discreetly –<br />
					Professional and Confidential.
				</h2>
				<p class="max-w-md text-lg leading-relaxed text-gray-800">
					Whether you are looking to sell a single apartment or a multi-family building, we offer a straightforward and confidential evaluation.
				</p>
			</div>

			<div class="mt-12 lg:mt-auto space-y-6">
				<div>
					<p class="font-bold text-black uppercase tracking-widest text-xs mb-2">Office</p>
					<p class="text-gray-900">Mutschellenstrasse 6</p>
					<p class="text-gray-900">8002 Zürich, Switzerland</p>
				</div>
				<div>
					<p class="font-bold text-black uppercase tracking-widest text-xs mb-2">Contact</p>
					<p class="text-gray-900">+41 44 508 52 57</p>
					<a href="mailto:info@vueag.ch" class="mt-1 block font-medium underline decoration-1 underline-offset-4 hover:decoration-2">
						info@vueag.ch
					</a>
				</div>
			</div>
		</div>

		<!-- Right Column: Form -->
		<div>
			<div class="mb-12 aspect-[4/3] w-full overflow-hidden bg-gray-100">
				<img
					src="/generated/image-a-portrait-of-a-professional-swiss-real--1771116544058-0.webp"
					alt="VUE AG Advisor"
					class="h-full w-full object-cover object-center filter"
				/>
			</div>

			<form class="flex flex-col gap-6">
				<div class="grid grid-cols-1 gap-6 md:grid-cols-2">
					<div class="flex flex-col gap-2">
						<label for="vorname" class="text-xs font-bold uppercase tracking-wider text-black">First Name</label>
						<input type="text" id="vorname" placeholder="First Name" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
					<div class="flex flex-col gap-2">
						<label for="nachname" class="text-xs font-bold uppercase tracking-wider text-black">Last Name</label>
						<input type="text" id="nachname" placeholder="Last Name" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
				</div>

				<div class="flex flex-col gap-2">
					<label for="email" class="text-xs font-bold uppercase tracking-wider text-black">Email Address</label>
					<input type="email" id="email" placeholder="Email" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="phone" class="text-xs font-bold uppercase tracking-wider text-black">Phone Number</label>
					<input type="tel" id="phone" placeholder="+41" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="message" class="text-xs font-bold uppercase tracking-wider text-black">Tell us about your property or inquiry.</label>
					<textarea id="message" rows="1" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none"></textarea>
				</div>

				<div class="mt-4 flex items-start gap-3">
					<input type="checkbox" id="privacy" class="mt-1 h-4 w-4 border-gray-300 text-black focus:ring-black" />
					<label for="privacy" class="text-xs leading-relaxed text-gray-600">
						I agree that my details and data will be collected and processed electronically to answer my inquiry. I have read the <a href="#" class="underline">Privacy Policy</a>.
					</label>
				</div>

				<button type="submit" class="mt-8 w-full bg-black py-4 px-8 text-center text-sm font-bold uppercase tracking-wider text-white transition-opacity hover:opacity-90">
					Submit Inquiry
				</button>
			</form>
		</div>
	</div>
</section>
