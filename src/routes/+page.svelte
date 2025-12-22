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
    <section class="w-full mb-32 md:mb-48 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Zürich cityscape with Lake Zürich" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-black/20 to-transparent"></div>
            <div class="absolute bottom-12 left-6 md:left-12 right-6 md:right-12 text-white">
                <h1 class="font-display text-4xl md:text-6xl lg:text-7xl mb-6 md:mb-8 max-w-4xl">Real estate on your terms</h1>
                <p class="text-lg md:text-xl font-light max-w-2xl mb-10 opacity-95">We help Zürich property owners sell quickly, quietly, and fairly—without the delays and headaches of the traditional process.</p>
                <a href="#contact" class="inline-block bg-white text-gray-900 px-8 py-4 text-sm hover:bg-gray-100 transition-colors">
                    Get a confidential valuation
                </a>
            </div>
        </div>
    </section>

    <!-- Value Proposition -->
    <section class="max-w-[1000px] mx-auto px-6 mb-32 md:mb-48">
        <div class="max-w-2xl mx-auto text-center mb-20">
            <h2 class="font-display text-3xl md:text-5xl text-gray-900 mb-8">Sell privately. Move forward confidently.</h2>
            <p class="text-gray-600 text-lg leading-relaxed font-light">
                Vue AG is a family-owned acquirer focused on building sustainable real estate portfolios. We buy directly from owners—no brokers, no auctions, no stress.
            </p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-16 gap-y-12 max-w-3xl mx-auto">
            <div>
                <h3 class="text-sm text-gray-400 mb-2">Speed</h3>
                <p class="text-gray-900 font-light">We make decisions in days, not months</p>
            </div>
            <div>
                <h3 class="text-sm text-gray-400 mb-2">Privacy</h3>
                <p class="text-gray-900 font-light">No listings, no signage, no publicity</p>
            </div>
            <div>
                <h3 class="text-sm text-gray-400 mb-2">Certainty</h3>
                <p class="text-gray-900 font-light">When we say yes, we mean it</p>
            </div>
            <div>
                <h3 class="text-sm text-gray-400 mb-2">Respect</h3>
                <p class="text-gray-900 font-light">We treat every owner and property with care</p>
            </div>
        </div>
    </section>

    <!-- Trust Section -->
    <section id="trust" class="max-w-[1200px] mx-auto px-6 mb-32 md:mb-48">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
            <div>
                <img src={handshakeImage} alt="Professional partnership" class="w-full aspect-[4/3] object-cover" />
            </div>
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-6">Built on trust. Backed by family.</h2>
                <p class="text-gray-600 font-light text-lg leading-relaxed">
                    We're not a fund. We're not a large developer. We're a small group of founders with skin in the game—focused on long-term, responsible growth.
                </p>
            </div>
        </div>
    </section>

    <!-- Portfolio Showcase -->
    <section id="portfolio" class="max-w-[1200px] mx-auto px-6 mb-32 md:mb-48">
        <div class="max-w-2xl mx-auto text-center mb-20">
            <h2 class="font-display text-3xl md:text-5xl text-gray-900 mb-6">Zürich roots. Urban focus.</h2>
            <p class="text-gray-600 font-light text-lg leading-relaxed">We specialize in acquiring multi-unit residential and mixed-use properties across the Zürich region.</p>
        </div>
        <img src={aerialView} alt="Zürich aerial view" class="w-full aspect-[16/9] object-cover mb-20" />
        <img src={buildingFacade} alt="Historic Zürich building" class="w-full aspect-[16/9] object-cover" />
    </section>

    <!-- Process Section -->
    <section id="process" class="max-w-[1000px] mx-auto px-6 mb-32 md:mb-48">
        <h2 class="font-display text-3xl md:text-5xl text-gray-900 mb-20 text-center">How it works</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-16">
            <div>
                <div class="text-5xl text-primary-600 mb-6">1</div>
                <h3 class="text-xl font-medium text-gray-900 mb-4">Initial conversation</h3>
                <p class="text-gray-600 font-light leading-relaxed">Speak directly with one of our founders. Share your situation, timeline, and expectations.</p>
            </div>
            <div>
                <div class="text-5xl text-primary-600 mb-6">2</div>
                <h3 class="text-xl font-medium text-gray-900 mb-4">Property evaluation</h3>
                <p class="text-gray-600 font-light leading-relaxed">We review your property details and conduct a discreet assessment. No public listings required.</p>
            </div>
            <div>
                <div class="text-5xl text-primary-600 mb-6">3</div>
                <h3 class="text-xl font-medium text-gray-900 mb-4">Fair offer & closing</h3>
                <p class="text-gray-600 font-light leading-relaxed">Receive a transparent offer within days. If accepted, we handle everything through closing.</p>
            </div>
        </div>
    </section>

    <!-- Penthouse Showcase -->
    <section class="w-full mb-32 md:mb-48">
        <img src={penthouseInterior} alt="Zürich penthouse interior" class="w-full h-[70vh] object-cover" />
    </section>

    <!-- Founders Section -->
    <section id="founders" class="max-w-[1200px] mx-auto px-6 mb-32 md:mb-48">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
            <div>
                <img src={foundersImage} alt="Vue AG founders - Amini brothers" class="w-full aspect-[4/3] object-cover" />
            </div>
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-12">Meet the founders</h2>
                <div class="space-y-8">
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Azim Amini</h3>
                        <p class="text-sm text-gray-500 mb-3">Mitgründer, Technologie & Akquise</p>
                        <p class="text-gray-600 font-light leading-relaxed">Leads technology strategy and property acquisition, bringing data-driven insights to every decision.</p>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Milad Amini</h3>
                        <p class="text-sm text-gray-500 mb-3">Mitgründer, Investitionen</p>
                        <p class="text-gray-600 font-light leading-relaxed">Oversees investment strategy and portfolio management with a focus on sustainable growth.</p>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium text-gray-900 mb-1">Nawid Amini</h3>
                        <p class="text-sm text-gray-500 mb-3">Mitgründer, Operations</p>
                        <p class="text-gray-600 font-light leading-relaxed">Manages day-to-day operations and ensures seamless execution from offer to closing.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact CTA -->
    <section id="contact" class="w-full bg-primary-900 text-white py-32 md:py-48">
        <div class="max-w-[900px] mx-auto px-6 text-center">
            <h2 class="font-display text-4xl md:text-6xl mb-8">Let's have a confidential conversation</h2>
            <p class="text-lg md:text-xl font-light mb-12 opacity-90">
                If you're thinking of selling or just want to understand your property's value, speak directly with one of our founders.
            </p>
            <div class="flex flex-col sm:flex-row gap-6 justify-center items-center">
                <a href="mailto:hello@vue.ag" class="bg-white text-gray-900 px-8 py-4 text-sm hover:bg-gray-100 transition-colors">
                    hello@vue.ag
                </a>
                <a href="tel:+41443334455" class="border border-white px-8 py-4 text-sm hover:bg-white hover:text-gray-900 transition-colors">
                    +41 44 333 44 55
                </a>
            </div>
        </div>
    </section>
</div>

