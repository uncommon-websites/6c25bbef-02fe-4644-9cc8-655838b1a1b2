<script lang="ts">
	import { ArrowRight, Zap, Bot, Database, BarChart3, Mail, MessageSquare, Calendar, CheckCircle2, Search, Plus, MoreHorizontal } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="mb-20 max-w-2xl">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			Control. Context. Ecosystem. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Configure templates with precision, trace every output to source material, and access expert templates from the marketplace — all in one platform.</span>
		</h2>
	</div>

	<div class="border border-gray-200 rounded-xl overflow-hidden bg-white shadow-sm">
		<!-- Row 1: Configure Templates -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Configure templates</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Set element-level rules and deck-level settings once. Generate infinite variations without regenerating entire presentations.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore templates <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center overflow-hidden relative">
				<!-- Template Configuration Mockup -->
				<div class="relative w-full max-w-lg">
					<!-- Master Template -->
					<div class="absolute top-0 left-0 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-64 z-10">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<Zap size={12} /> Master Template
						</div>
						<div class="text-sm font-medium text-gray-900">Client Pitch Deck</div>
						<div class="text-xs text-gray-400 mt-1">Configure once, generate variations</div>
					</div>

					<!-- Path -->
					<svg class="absolute top-16 left-32 w-full h-40 pointer-events-none" style="z-index: 0;">
						<path d="M 0 0 V 20 H 100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
						<path d="M 0 0 V 20 H -100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
					</svg>

					<!-- Variation 1 -->
					<div class="absolute top-32 -left-20 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<div class="w-2 h-2 rounded-full bg-blue-500"></div> Variation
						</div>
						<div class="text-sm font-medium text-gray-900">Investor Version</div>
						<div class="mt-2 flex gap-2">
							<span class="px-2 py-0.5 bg-purple-100 text-purple-700 text-[10px] rounded">Financial</span>
							<span class="px-2 py-0.5 bg-blue-100 text-blue-700 text-[10px] rounded">Formal</span>
						</div>
					</div>

					<!-- Variation 2 -->
					<div class="absolute top-32 left-40 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<div class="w-2 h-2 rounded-full bg-green-500"></div> Variation
						</div>
						<div class="text-sm font-medium text-gray-900">Partner Version</div>
						<div class="mt-2 flex gap-2">
							<span class="px-2 py-0.5 bg-green-100 text-green-700 text-[10px] rounded">Strategic</span>
							<span class="px-2 py-0.5 bg-orange-100 text-orange-700 text-[10px] rounded">Brief</span>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<path d="M50 0L93.3013 25V75L50 100L6.69873 75V25L50 0Z" stroke="black" stroke-width="1"/>
						<path d="M50 0V50M93.3013 25L50 50M93.3013 75L50 50M50 100V50M6.69873 75L50 50M6.69873 25L50 50" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 2: Precision AI Editing -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Precision AI editing</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Edit specific elements without regenerating entire decks. Surgical precision meets AI power for professional workflows.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore editing <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="bg-white rounded-xl shadow-sm border border-gray-200 w-full max-w-md overflow-hidden">
					<div class="p-3 border-b border-gray-100 flex items-center gap-2 bg-gray-50/50">
						<Bot size={16} class="text-purple-600" />
						<span class="text-xs font-medium text-gray-700">Precision editing mode</span>
					</div>
					<div class="p-4 space-y-4">
						<div class="flex gap-3">
							<div class="w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center flex-shrink-0">
								<Bot size={16} class="text-purple-600" />
							</div>
							<div class="flex-1">
								<div class="bg-gray-50 rounded-lg p-3 text-sm text-gray-800 mb-2">
									<p class="font-medium mb-1">Edit slide 3: Market Analysis</p>
									<p class="text-gray-500 text-xs">Make the tone more formal and add CAGR data</p>
								</div>
								
								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 mb-2 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<div class="w-4 h-4 rounded bg-blue-100 flex items-center justify-center text-[10px] text-blue-600">✓</div>
										<span class="font-medium">Tone adjusted to professional</span>
									</div>
									<p class="text-gray-500 text-xs">Updated language to match enterprise standards</p>
								</div>

								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<div class="w-4 h-4 rounded bg-blue-100 flex items-center justify-center text-[10px] text-blue-600">✓</div>
										<span class="font-medium">Added 13.9% CAGR metric</span>
									</div>
									<p class="text-gray-500 text-xs">Sourced from market-research-2024.pdf</p>
								</div>
							</div>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<circle cx="50" cy="50" r="40" stroke="black" stroke-width="1"/>
						<path d="M50 10 C 70 30, 70 70, 50 90 C 30 70, 30 30, 50 10" stroke="black" stroke-width="1" fill="none"/>
						<path d="M10 50 C 30 30, 70 30, 90 50 C 70 70, 30 70, 10 50" stroke="black" stroke-width="1" fill="none"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 3: Mind Map with Citations -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Mind map with citations</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Trace every output back to source material. Full transparency and control over your AI-generated content.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore mind map <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="relative w-full max-w-md h-64 flex items-center justify-center">
					<!-- Center Slide -->
					<div class="w-20 h-16 bg-white border-2 border-black rounded flex items-center justify-center z-10 shadow-lg">
						<span class="text-black font-bold text-xs">Slide 3</span>
					</div>

					<!-- Connecting Lines -->
					<svg class="absolute inset-0 w-full h-full pointer-events-none">
						<line x1="50%" y1="50%" x2="20%" y2="20%" stroke="#e5e7eb" stroke-width="2" />
						<line x1="50%" y1="50%" x2="80%" y2="20%" stroke="#e5e7eb" stroke-width="2" />
						<line x1="50%" y1="50%" x2="20%" y2="80%" stroke="#e5e7eb" stroke-width="2" />
						<line x1="50%" y1="50%" x2="80%" y2="80%" stroke="#e5e7eb" stroke-width="2" />
						<line x1="50%" y1="50%" x2="50%" y2="15%" stroke="#e5e7eb" stroke-width="2" />
						<line x1="50%" y1="50%" x2="50%" y2="85%" stroke="#e5e7eb" stroke-width="2" />
					</svg>

					<!-- Source Citations -->
					<div class="absolute top-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						📄 research.pdf
					</div>
					<div class="absolute top-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						📊 data.xlsx
					</div>
					<div class="absolute bottom-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						🔗 article.com
					</div>
					<div class="absolute bottom-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						📝 notes.txt
					</div>
					<div class="absolute top-4 left-1/2 -translate-x-1/2 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						💼 brief.docx
					</div>
					<div class="absolute bottom-4 left-1/2 -translate-x-1/2 bg-white p-2 rounded-lg shadow-sm border border-gray-100 text-[10px] text-gray-600">
						📈 stats.csv
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<rect x="25" y="25" width="50" height="50" stroke="black" stroke-width="1" transform="rotate(45 50 50)"/>
						<rect x="25" y="25" width="50" height="50" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 4: Template Marketplace -->
		<div class="grid grid-cols-1 md:grid-cols-3">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Template marketplace</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Access expert templates from industry professionals. Earn credits when your templates are used by others.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore marketplace <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="grid grid-cols-2 gap-6 w-full max-w-lg">
					<!-- Template Card 1 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="bg-gradient-to-br from-blue-100 to-purple-100 h-24 rounded mb-3 flex items-center justify-center">
							<span class="text-xs text-gray-600">Consultant Pitch</span>
						</div>
						<div class="text-sm font-medium text-gray-900 mb-1">Strategy Deck</div>
						<div class="flex items-center gap-2 mb-2">
							<div class="w-5 h-5 rounded-full bg-gray-200"></div>
							<span class="text-xs text-gray-500">by Alex K.</span>
						</div>
						<div class="flex items-center justify-between">
							<span class="text-xs text-gray-400">2.4k uses</span>
							<span class="text-xs font-medium text-blue-600">Use template</span>
						</div>
					</div>

					<!-- Template Card 2 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="bg-gradient-to-br from-green-100 to-blue-100 h-24 rounded mb-3 flex items-center justify-center">
							<span class="text-xs text-gray-600">Investor Deck</span>
						</div>
						<div class="text-sm font-medium text-gray-900 mb-1">Fundraising</div>
						<div class="flex items-center gap-2 mb-2">
							<div class="w-5 h-5 rounded-full bg-gray-200"></div>
							<span class="text-xs text-gray-500">by Sarah M.</span>
						</div>
						<div class="flex items-center justify-between">
							<span class="text-xs text-gray-400">1.8k uses</span>
							<span class="text-xs font-medium text-blue-600">Use template</span>
						</div>
					</div>

					<!-- Template Card 3 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="bg-gradient-to-br from-orange-100 to-red-100 h-24 rounded mb-3 flex items-center justify-center">
							<span class="text-xs text-gray-600">Sales Pitch</span>
						</div>
						<div class="text-sm font-medium text-gray-900 mb-1">Enterprise Sales</div>
						<div class="flex items-center gap-2 mb-2">
							<div class="w-5 h-5 rounded-full bg-gray-200"></div>
							<span class="text-xs text-gray-500">by Mike R.</span>
						</div>
						<div class="flex items-center justify-between">
							<span class="text-xs text-gray-400">3.1k uses</span>
							<span class="text-xs font-medium text-blue-600">Use template</span>
						</div>
					</div>

					<!-- Template Card 4 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="bg-gradient-to-br from-purple-100 to-pink-100 h-24 rounded mb-3 flex items-center justify-center">
							<span class="text-xs text-gray-600">Product Launch</span>
						</div>
						<div class="text-sm font-medium text-gray-900 mb-1">Go-to-Market</div>
						<div class="flex items-center gap-2 mb-2">
							<div class="w-5 h-5 rounded-full bg-gray-200"></div>
							<span class="text-xs text-gray-500">by Lisa T.</span>
						</div>
						<div class="flex items-center justify-between">
							<span class="text-xs text-gray-400">1.5k uses</span>
							<span class="text-xs font-medium text-blue-600">Use template</span>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<path d="M20 80 L 50 30 L 80 80 Z" stroke="black" stroke-width="1"/>
						<path d="M20 80 L 20 50 L 50 30" stroke="black" stroke-width="1"/>
						<path d="M80 80 L 80 50 L 50 30" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
</section>
