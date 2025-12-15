<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-brand-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-brand-primary)]"></span>
                        <span class="text-white text-sm font-medium">Cloud ERP</span>
                        <span class="text-gray-400 text-sm">for Balkans</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Automate your restaurant. Cut costs instantly.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Cloud-based ERP that eliminates manual errors and reduces operational costs through real-time inventory synchronization. Built for restaurants and retail businesses across Montenegro and the Balkans.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Start Free Trial
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Calculate Your Savings
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Inventory -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Inventory Status</div>
                                <div class="h-8 w-24 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">In Stock</div>
                            </div>
                            <div class="space-y-3">
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-sm text-gray-700">Tomatoes</span>
                                    <span class="text-sm font-bold">45 kg</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-gray-50 rounded-lg">
                                    <span class="text-sm text-gray-700">Olive Oil</span>
                                    <span class="text-sm font-bold">12 L</span>
                                </div>
                                <div class="flex justify-between items-center p-3 bg-red-50 rounded-lg border border-red-100">
                                    <span class="text-sm text-red-700">Cheese</span>
                                    <span class="text-sm font-bold text-red-700">2 kg ⚠️</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Dashboard -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <img src="/generated/image-clean-dashboard-interface-showing-sales--1765807951629-2.webp" alt="e-firma Dashboard" class="w-full h-full object-cover" />
                    </div>

                    <!-- Card 3 - Invoice -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Invoice #2847</div>
                                <div class="h-8 w-24 bg-[var(--color-brand-primary)]/20 rounded text-[var(--color-brand-primary)] text-xs flex items-center justify-center font-bold">€284.50</div>
                            </div>
                            <div class="space-y-3">
                                <div class="flex justify-between text-sm">
                                    <span class="text-gray-600">Table 12</span>
                                    <span class="font-medium">€284.50</span>
                                </div>
                                <div class="h-px bg-gray-200"></div>
                                <div class="flex justify-between text-xs text-gray-500">
                                    <span>Generated: 15:24</span>
                                    <span>Auto-synced ✓</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by restaurants and retail businesses across Montenegro</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50">
                    <div class="text-white font-bold text-lg tracking-wider">RESTAURANT PORTO</div>
                    <div class="text-white font-bold text-lg tracking-wider">CAFÉ CENTRAL</div>
                    <div class="text-white font-bold text-lg tracking-wider">MARKET PLUS</div>
                    <div class="text-white font-bold text-lg tracking-wider">BISTRO ADRIATIC</div>
                    <div class="text-white font-bold text-lg tracking-wider">RETAIL PRO</div>
                </div>
            </div>
        </section>

        <!-- e-firma Platform Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-brand-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">e-firma Platform</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">A cloud ERP system.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">That actually saves you money.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Teal Card -->
                    <div class="bg-gradient-to-br from-[#0d9488] to-[#115e59] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Dashboard Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="text-white/60 text-[10px] uppercase tracking-wider font-medium mb-2">Today's Revenue</div>
                                <div class="text-white font-bold text-3xl mb-4">€2,847.50</div>
                                <div class="flex gap-2 text-xs">
                                    <div class="bg-white/20 px-3 py-1 rounded-full text-white">+12% vs yesterday</div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-orange-100 flex items-center justify-center text-orange-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"/></svg>
                                    </div>
                                    Restaurant Module
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-teal-500/30 flex items-center justify-center text-teal-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 2a4 4 0 00-4 4v1H5a1 1 0 00-.994.89l-1 9A1 1 0 004 18h12a1 1 0 00.994-1.11l-1-9A1 1 0 0015 7h-1V6a4 4 0 00-4-4zm2 5V6a2 2 0 10-4 0v1h4zm-6 3a1 1 0 112 0 1 1 0 01-2 0zm7-1a1 1 0 100 2 1 1 0 000-2z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Retail Module
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Grow without the growing pains.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            From single location to multi-site operations. e-firma scales with your business, eliminating manual work and reducing costs at every stage of growth.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">e-firma Modules</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">One platform for your entire business operation.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">From inventory to invoicing.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore all modules
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-brand-primary)]"></span>
                                Inventory Management
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Automated Invoicing</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Order Management</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Financial Reporting</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Multi-location Sync</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Integration Hub</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Real-time Inventory Management" 
                            description="Never run out of stock again. Track inventory levels across all locations in real-time, with automatic alerts when items run low and seamless supplier integration."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Automated Invoicing" 
                            description="Eliminate manual invoice creation. Generate and send invoices automatically with every transaction, synced instantly across all your systems and accounting software."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Order Management" 
                            description="Streamline from order to delivery. Manage supplier orders, track deliveries, and maintain optimal stock levels with intelligent reordering suggestions."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Financial Reporting" 
                            description="Make data-driven decisions. Access real-time financial reports, profit margins, and cost analysis to identify savings opportunities and optimize operations."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Multi-location Sync" 
                            description="Manage all locations from one dashboard. Real-time synchronization ensures consistent inventory, pricing, and reporting across every business location."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Integration Hub" 
                            description="Connect your existing tools. Seamlessly integrate with POS systems, accounting software, and payment processors without disrupting your workflow."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Multi-location Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-teal-100 to-cyan-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-teal-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        From single restaurant to multi-location chain — e-firma grows with your business across Montenegro and beyond.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See pricing plans
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by restaurants and retailers across Montenegro. Hear from our customers.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Case Study Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 opacity-30">
                                <img src="/generated/image-montenegrin-restaurant-interior-with-mod-1765807959889-5.webp" alt="Restaurant" class="w-full h-full object-cover" />
                            </div>
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/70 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">Restaurant Porto</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-brand-primary)] flex items-center justify-center text-black font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="3" y="3" width="18" height="18" rx="2" stroke="white" stroke-width="2"/>
                                            <path d="M8 12h8M12 8v8" stroke="white" stroke-width="2" stroke-linecap="round"/>
                                        </svg>
                                        e-firma
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    How Restaurant Porto reduced costs by 35% and eliminated inventory errors
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 opacity-20">
                                    <img src="/generated/image-happy-restaurant-staff-collaborating-wit-1765807954524-3.webp" alt="Team" class="w-full h-full object-cover" />
                                </div>
                                <div class="absolute inset-0 bg-gradient-to-br from-teal-900/60 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white text-sm mb-2 font-medium">Café Central</p>
                                    <p class="text-gray-400 text-xs">3 locations synced</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-end">
                                <div class="absolute inset-0 opacity-20">
                                    <img src="/generated/image-small-business-owner-smiling-while-revie-1765807956977-4.webp" alt="Owner" class="w-full h-full object-cover" />
                                </div>
                                <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/60 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white text-sm mb-2 font-medium">Market Plus</p>
                                    <p class="text-gray-400 text-xs">Retail success story</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Stop losing money to manual errors. <span class="text-[var(--color-brand-primary)]">Start saving today.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Free ROI calculator shows exactly how much e-firma can save your business. No credit card required.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                            Calculate Your Savings
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        POS systems. Accounting software.<br>
                        Payment gateways. <span class="text-gray-400">Whatever you use,<br>e-firma integrates seamlessly.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Square POS', 'QuickBooks', 'Stripe', 'Xero', 'PayPal', 'WooCommerce', 'Shopify', 'Sage'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-lg uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn how to optimize your operations.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <img src="/generated/image-restaurant-owner-confidently-using-a-tab-1765807945811-0.webp" alt="Restaurant operations" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Operations Guide</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">5 ways restaurants lose money through inventory mismanagement</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <img src="/generated/image-modern-retail-store-owner-checking-inven-1765807948932-1.webp" alt="Retail automation" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Case Study</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">How Montenegrin retailers are cutting costs with cloud ERP</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

