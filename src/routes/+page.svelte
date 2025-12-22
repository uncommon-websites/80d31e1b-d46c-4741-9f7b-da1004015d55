<script lang="ts">
    // Vue AG Real Estate Images
    const heroImage = "/generated/image-elegant-zrich-cityscape-with-lake-zrich--1766403318708-0.webp";
    const foundersImage = "/generated/image-three-professional-swiss-businessmen-bro-1766403322440-1.webp";
    const buildingFacade = "/generated/image-elegant-historic-zrich-apartment-buildin-1766403325277-2.webp";
    const penthouseInterior = "/generated/image-modern-luxury-zrich-penthouse-interior-w-1766403328198-3.webp";
    const handshakeImage = "/generated/image-professional-handshake-between-business--1766403330963-4.webp";
    const oldTownStreet = "/generated/image-zrich-old-town-cobblestone-street-with-t-1766403333660-5.webp";
    const officeInterior = "/generated/image-modern-minimalist-swiss-office-interior--1766403336543-6.webp";
    const aerialView = "/generated/image-aerial-view-of-zrich-residential-neighbo-1766403339247-7.webp";
</script>

<div class="w-full">
    <!-- Hero Section -->
    <section class="w-full mb-16 md:mb-24 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Zürich cityscape with Lake Zürich" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/20 to-transparent"></div>
            <div class="absolute bottom-12 left-6 md:left-12 right-6 md:right-12 text-white">
                <h1 class="font-display text-4xl md:text-6xl lg:text-7xl mb-4 md:mb-6 max-w-4xl">Real estate on your terms</h1>
                <p class="text-lg md:text-xl font-light max-w-2xl mb-8 opacity-95">We help Zürich property owners sell quickly, quietly, and fairly—without the delays and headaches of the traditional process.</p>
                <a href="#contact" class="inline-block bg-white text-gray-900 px-8 py-4 text-sm uppercase tracking-widest hover:bg-gray-100 transition-colors">
                    Get a confidential valuation
                </a>
            </div>
        </div>
    </section>

    <!-- Value Proposition -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-8">Sell privately. Move forward confidently.</h2>
                <div class="text-gray-600 text-base leading-relaxed space-y-4 max-w-md font-light">
                    <p>
                        Vue AG is a family-owned acquirer focused on building sustainable real estate portfolios. We buy directly from owners—no brokers, no auctions, no stress.
                    </p>
                    <p>
                        Our reputation matters. That's why most of our partnerships come through trusted notaries, lawyers, and word of mouth.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-1 gap-8">
                <div>
                    <h3 class="text-sm uppercase tracking-wider text-gray-400 mb-2">Speed</h3>
                    <p class="text-gray-900 font-light">We make decisions in days, not months</p>
                </div>
                <div>
                    <h3 class="text-sm uppercase tracking-wider text-gray-400 mb-2">Privacy</h3>
                    <p class="text-gray-900 font-light">No listings, no signage, no publicity</p>
                </div>
                <div>
                    <h3 class="text-sm uppercase tracking-wider text-gray-400 mb-2">Certainty</h3>
                    <p class="text-gray-900 font-light">When we say yes, we mean it</p>
                </div>
                <div>
                    <h3 class="text-sm uppercase tracking-wider text-gray-400 mb-2">Respect</h3>
                    <p class="text-gray-900 font-light">We treat every owner and property with care</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Trust Section -->
    <section id="trust" class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
            <div class="md:col-span-5 md:col-start-2">
                <img src={handshakeImage} alt="Professional partnership" class="w-full aspect-[4/3] object-cover mb-8" />
                <div class="max-w-md">
                    <h2 class="font-display text-3xl text-gray-900 mb-6">Built on trust. Backed by family.</h2>
                    <p class="text-gray-600 font-light leading-relaxed mb-4">
                        We're not a fund. We're not a large developer. We're a small group of founders with skin in the game—focused on long-term, responsible growth.
                    </p>
                    <p class="text-gray-600 font-light leading-relaxed">
                        Our reputation matters. That's why most of our partnerships come through trusted notaries, lawyers, and word of mouth.
                    </p>
                </div>
            </div>
            <div class="md:col-span-5 md:col-start-8">
                 <img src={officeInterior} alt="Vue AG office" class="w-full aspect-[4/3] object-cover" />
            </div>
        </div>
    </section>

    <!-- Portfolio Showcase -->
    <section id="portfolio" class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="mb-12">
            <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-4">Zürich roots. Urban focus.</h2>
            <p class="text-gray-600 font-light max-w-2xl">We specialize in acquiring multi-unit residential and mixed-use properties across the Zürich region. We preserve what works and improve what doesn't—one building at a time.</p>
        </div>
        <img src={aerialView} alt="Zürich aerial view" class="w-full aspect-[16/9] md:aspect-[21/9] object-cover" />
    </section>

    <!-- Portfolio Grid -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
                <img src={buildingFacade} alt="Historic Zürich building" class="w-full aspect-[3/4] object-cover" />
            </div>
            <div class="flex flex-col justify-between">
                <img src={oldTownStreet} alt="Zürich old town" class="w-full aspect-[3/4] object-cover mb-8" />
                <div class="max-w-md ml-auto">
                     <h3 class="text-sm uppercase tracking-wider text-gray-400 mb-3">Who we buy from</h3>
                     <ul class="text-gray-600 font-light space-y-2">
                        <li>• Families managing inheritance or succession</li>
                        <li>• Owners of older properties needing renovation</li>
                        <li>• Individuals tired of bureaucracy or delays</li>
                        <li>• Foundations seeking clean, quiet exits</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section id="process" class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-16 text-center">How it works</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
            <div class="text-center">
                <div class="w-16 h-16 bg-primary-100 text-primary-700 rounded-full flex items-center justify-center text-2xl font-display mx-auto mb-6">1</div>
                <h3 class="text-lg font-medium text-gray-900 mb-3">Initial conversation</h3>
                <p class="text-gray-600 font-light text-sm leading-relaxed">Speak directly with one of our founders. Share your situation, timeline, and expectations.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 bg-primary-100 text-primary-700 rounded-full flex items-center justify-center text-2xl font-display mx-auto mb-6">2</div>
                <h3 class="text-lg font-medium text-gray-900 mb-3">Property evaluation</h3>
                <p class="text-gray-600 font-light text-sm leading-relaxed">We review your property details and conduct a discreet assessment. No public listings required.</p>
            </div>
            <div class="text-center">
                <div class="w-16 h-16 bg-primary-100 text-primary-700 rounded-full flex items-center justify-center text-2xl font-display mx-auto mb-6">3</div>
                <h3 class="text-lg font-medium text-gray-900 mb-3">Fair offer & closing</h3>
                <p class="text-gray-600 font-light text-sm leading-relaxed">Receive a transparent offer within days. If accepted, we handle everything through closing.</p>
            </div>
        </div>
    </section>

    <!-- Penthouse Showcase -->
    <section class="w-full mb-24 md:mb-32">
        <img src={penthouseInterior} alt="Zürich penthouse interior" class="w-full h-[70vh] object-cover" />
    </section>

    <!-- Founders Section -->
    <section id="founders" class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-16 items-center">
            <div>
                <img src={foundersImage} alt="Vue AG founders - Amini brothers" class="w-full aspect-[4/3] object-cover" />
            </div>
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-8">Meet the founders</h2>
                <div class="space-y-6">
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Azim Amini</h3>
                        <p class="text-sm text-gray-500 uppercase tracking-wider mb-2">Mitgründer, Technologie & Akquise</p>
                        <p class="text-gray-600 font-light text-sm leading-relaxed">Leads technology strategy and property acquisition, bringing data-driven insights to every decision.</p>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Milad Amini</h3>
                        <p class="text-sm text-gray-500 uppercase tracking-wider mb-2">Mitgründer, Investitionen</p>
                        <p class="text-gray-600 font-light text-sm leading-relaxed">Oversees investment strategy and portfolio management with a focus on sustainable growth.</p>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Nawid Amini</h3>
                        <p class="text-sm text-gray-500 uppercase tracking-wider mb-2">Mitgründer, Operations</p>
                        <p class="text-gray-600 font-light text-sm leading-relaxed">Manages day-to-day operations and ensures seamless execution from offer to closing.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Vue -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="bg-gray-50 p-12 md:p-16">
            <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-8 text-center">Why property owners choose Vue</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-3xl mx-auto">
                <div class="border-l-2 border-primary-600 pl-6">
                    <h3 class="text-lg font-medium text-gray-900 mb-2">Discreet transactions</h3>
                    <p class="text-gray-600 font-light text-sm leading-relaxed">Off-market acquisitions that protect your privacy and maintain discretion throughout the process.</p>
                </div>
                <div class="border-l-2 border-primary-600 pl-6">
                    <h3 class="text-lg font-medium text-gray-900 mb-2">Fair, transparent offers</h3>
                    <p class="text-gray-600 font-light text-sm leading-relaxed">Clear pricing based on thorough market analysis and property evaluation.</p>
                </div>
                <div class="border-l-2 border-primary-600 pl-6">
                    <h3 class="text-lg font-medium text-gray-900 mb-2">Family-backed stability</h3>
                    <p class="text-gray-600 font-light text-sm leading-relaxed">Decisions made by founders with skin in the game, not distant committees.</p>
                </div>
                <div class="border-l-2 border-primary-600 pl-6">
                    <h3 class="text-lg font-medium text-gray-900 mb-2">Notary network trust</h3>
                    <p class="text-gray-600 font-light text-sm leading-relaxed">Most partnerships come through trusted legal professionals who know our reputation.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact CTA -->
    <section id="contact" class="w-full bg-primary-900 text-white py-24 md:py-32">
        <div class="max-w-[1200px] mx-auto px-6 text-center">
            <h2 class="font-display text-4xl md:text-5xl mb-6">Let's have a confidential conversation</h2>
            <p class="text-lg md:text-xl font-light mb-12 opacity-90 max-w-3xl mx-auto">
                If you're thinking of selling or just want to understand your property's value, speak directly with one of our founders. No pressure. No obligations. Just straight answers.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center mb-8">
                <a href="mailto:hello@vue.ag" class="bg-white text-gray-900 px-8 py-4 text-sm uppercase tracking-widest hover:bg-gray-100 transition-colors">
                    hello@vue.ag
                </a>
                <a href="tel:+41443334455" class="border border-white px-8 py-4 text-sm uppercase tracking-widest hover:bg-white hover:text-gray-900 transition-colors">
                    +41 44 333 44 55
                </a>
            </div>
            <p class="text-sm opacity-75">Zürich, Switzerland</p>
        </div>
    </section>
</div>

