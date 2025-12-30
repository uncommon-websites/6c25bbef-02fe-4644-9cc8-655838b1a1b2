<script lang="ts">
	import { ArrowRight, ChevronDown, Search, Bell, CheckSquare, Mail, BarChart2, Zap, Layout, Users, Briefcase, Building2, Plus, MoreHorizontal, Filter, RefreshCw, Download } from 'lucide-svelte';
</script>

<section class="pt-40 pb-20 px-6 text-center max-w-[1400px] mx-auto">
	<a href="#" class="inline-flex items-center gap-2 text-xs font-medium text-gray-500 hover:text-black mb-8 border border-gray-200 rounded-full px-3 py-1 bg-white hover:border-gray-300 transition-colors">
		Raising $1M pre-seed — Join the waitlist
		<ArrowRight size={12} />
	</a>

	<h1 class="text-[56px] leading-[1.1] font-serif tracking-tight text-gray-900 mb-6 max-w-4xl mx-auto">
		Precision AI editing<br/>for presentations.
	</h1>

	<p class="text-lg text-gray-500 mb-10 max-w-xl mx-auto text-balance">
		Transform existing presentations into AI-powered templates. Configure once, generate variations — without regenerating entire decks.
	</p>

	<div class="flex items-center justify-center gap-4 mb-20">
		<a href="#" class="bg-black text-white text-sm font-medium px-5 py-2.5 rounded-lg hover:bg-gray-800 transition-colors">
			Start for free
		</a>
		<a href="#" class="text-sm font-medium text-gray-600 hover:text-black border border-gray-200 px-5 py-2.5 rounded-lg hover:border-gray-300 transition-colors">
			Talk to sales
		</a>
	</div>

	<!-- Presentation Editor Preview -->
	<div class="relative rounded-xl overflow-hidden shadow-2xl border border-gray-200 bg-white text-left mx-auto max-w-[1200px]">
		<!-- Tabs -->
		<div class="flex border-b border-gray-200 bg-gray-50/50">
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">Templates</button>
			<button class="px-8 py-3 text-xs font-medium text-black border-b-2 border-black bg-white">Editor</button>
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">Mind Map</button>
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">Settings</button>
		</div>

		<!-- UI Container -->
		<div class="flex h-[600px] bg-white">
			<!-- Sidebar -->
			<div class="w-[240px] border-r border-gray-200 flex flex-col text-[13px] text-gray-600">
				<div class="p-3 flex items-center gap-2 font-medium text-black border-b border-gray-100">
					<div class="w-5 h-5 bg-black rounded flex items-center justify-center text-white text-[10px]">S</div>
					Q3 Strategy Deck
					<ChevronDown size={14} class="ml-auto opacity-50" />
				</div>
				
				<div class="p-2 space-y-0.5">
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Search size={14} /> Quick actions
						<div class="ml-auto text-[10px] border border-gray-200 rounded px-1">⌘K</div>
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Bell size={14} /> AI Suggestions
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<CheckSquare size={14} /> Templates
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 bg-gray-100 text-black font-medium rounded cursor-pointer">
						<Layout size={14} /> Slides
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<BarChart2 size={14} /> Mind Map
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Zap size={14} /> Settings
					</div>
				</div>

				<div class="mt-2 px-4 text-[11px] font-medium text-gray-400">Presentations</div>
				<div class="p-2 space-y-0.5">
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Building2 size={14} class="text-blue-500" /> Client Pitch
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Users size={14} class="text-green-500" /> Team Update
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 bg-gray-50 rounded cursor-pointer">
						<Briefcase size={14} class="text-orange-500" /> Q3 Strategy
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Layout size={14} class="text-purple-500" /> Investor Deck
					</div>
				</div>
			</div>

			<!-- Main Content -->
			<div class="flex-1 flex flex-col bg-gray-50/30">
				<!-- Header -->
				<div class="h-14 border-b border-gray-200 flex items-center justify-between px-6 bg-white">
					<div class="flex items-center gap-2 text-sm text-gray-500">
						<Layout size={16} />
						<span>Slides</span>
						<span class="text-gray-300">/</span>
						<span class="text-black font-medium">Market Analysis</span>
					</div>
					<div class="flex items-center gap-3">
						<div class="flex -space-x-2">
							<div class="w-6 h-6 rounded-full bg-blue-100 border-2 border-white flex items-center justify-center text-[10px]">AK</div>
							<div class="w-6 h-6 rounded-full bg-green-100 border-2 border-white flex items-center justify-center text-[10px]">DM</div>
						</div>
						<button class="text-xs font-medium text-gray-600 hover:text-black flex items-center gap-1">
							Export
						</button>
					</div>
				</div>

				<!-- Slide Editor Content -->
				<div class="p-6 overflow-hidden">
					<div class="mb-6 flex items-center justify-between">
						<div>
							<h2 class="text-lg font-semibold text-gray-900">Market Analysis</h2>
							<p class="text-sm text-gray-500">AI-generated content with precision editing controls and template configurations.</p>
						</div>
						<div class="flex items-center gap-2">
							<button class="text-xs font-medium text-gray-500 hover:text-black flex items-center gap-1 px-2 py-1">
								<RefreshCw size={12} /> Regenerate
							</button>
							<button class="bg-blue-600 text-white text-xs font-medium px-3 py-1.5 rounded-md hover:bg-blue-700 flex items-center gap-1">
								<Plus size={12} /> Add slide
							</button>
						</div>
					</div>

					<div class="grid grid-cols-5 gap-6 h-full">
						<!-- Slide Preview -->
						<div class="col-span-3 bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
							<div class="flex items-center justify-between mb-4">
								<h3 class="text-sm font-medium text-gray-900">Market Opportunity</h3>
								<div class="flex items-center gap-2">
									<button class="text-xs text-blue-600 font-medium">Edit with AI</button>
									<MoreHorizontal size={14} class="text-gray-400" />
								</div>
							</div>
							
							<!-- Mock Slide Content -->
							<div class="bg-gradient-to-br from-blue-50 to-purple-50 rounded-lg p-8 h-[300px] flex flex-col justify-between">
								<div>
									<h4 class="text-2xl font-bold text-gray-900 mb-4">$74B Market Opportunity</h4>
									<p class="text-sm text-gray-600 leading-relaxed mb-6">
										Enterprise productivity and creativity tools represent a massive addressable market, growing at 13.9% CAGR through 2030.
									</p>
								</div>
								
								<div class="grid grid-cols-2 gap-4">
									<div class="bg-white/80 backdrop-blur rounded p-3">
										<div class="text-xs text-gray-500 mb-1">Productivity</div>
										<div class="text-lg font-bold text-gray-900">$62.5B</div>
									</div>
									<div class="bg-white/80 backdrop-blur rounded p-3">
										<div class="text-xs text-gray-500 mb-1">Design Tools</div>
										<div class="text-lg font-bold text-gray-900">$11.3B</div>
									</div>
								</div>
							</div>
						</div>

						<!-- AI Controls Panel -->
						<div class="col-span-2 bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
							<div class="flex items-center justify-between mb-4">
								<h3 class="text-sm font-medium text-gray-900">Precision Controls</h3>
								<MoreHorizontal size={14} class="text-gray-400" />
							</div>
							
							<div class="space-y-4">
								<div>
									<div class="text-xs text-gray-500 mb-2">Tone</div>
									<div class="flex gap-2">
										<button class="px-3 py-1 bg-blue-100 text-blue-700 text-xs rounded-full font-medium">Professional</button>
										<button class="px-3 py-1 bg-gray-100 text-gray-600 text-xs rounded-full">Casual</button>
									</div>
								</div>
								
								<div>
									<div class="text-xs text-gray-500 mb-2">Detail Level</div>
									<div class="flex items-center gap-2">
										<div class="flex-1 bg-gray-200 h-1 rounded-full overflow-hidden">
											<div class="bg-blue-600 h-full w-2/3"></div>
										</div>
										<span class="text-xs text-gray-600">High</span>
									</div>
								</div>
								
								<div>
									<div class="text-xs text-gray-500 mb-2">Data Source</div>
									<div class="text-xs text-gray-900 bg-gray-50 rounded p-2 border border-gray-100">
										market-research-2024.pdf
									</div>
								</div>
								
								<div>
									<div class="text-xs text-gray-500 mb-2">Custom Instructions</div>
									<div class="text-xs text-gray-600 bg-gray-50 rounded p-2 border border-gray-100 h-20 overflow-hidden">
										Focus on enterprise segment. Include CAGR data. Use professional tone...
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Logos -->
	<div class="mt-20 flex flex-wrap justify-center items-center gap-12 opacity-60 grayscale">
		<span class="font-bold text-xl">McKinsey</span>
		<span class="font-bold text-xl">BCG</span>
		<span class="font-bold text-xl">Bain</span>
		<span class="font-bold text-xl">Deloitte</span>
		<span class="font-bold text-xl">Slalom</span>
		<span class="font-bold text-xl">Accenture</span>
	</div>
</section>
