<script lang="ts">
	import { Mail, Calendar, Database, Activity, Search, Bell, CheckSquare, BarChart2, Zap, MoreHorizontal, Filter, RefreshCw, Plus } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20 text-center">
	<div class="max-w-3xl mx-auto mb-12">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			From idea to presentation. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Upload research, set your configuration, and watch Sage transform your materials into professional presentations with full source traceability.</span>
		</h2>
		<button class="mt-8 px-5 py-2.5 bg-black text-white rounded-lg text-sm font-medium hover:bg-gray-800 transition-colors">
			Start for free
		</button>
	</div>

	<!-- Tabs -->
	<div class="flex justify-center gap-4 mb-12">
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-900 shadow-sm hover:bg-gray-50">
			<Mail size={14} /> Upload sources
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Calendar size={14} /> Configure template
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Activity size={14} /> Generate deck
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Database size={14} /> Export PPTX
		</button>
	</div>

	<!-- UI Preview -->
	<div class="relative bg-white rounded-xl border border-gray-200 shadow-xl overflow-hidden text-left max-w-5xl mx-auto">
		<!-- Header -->
		<div class="h-14 border-b border-gray-200 flex items-center justify-between px-6 bg-white">
			<div class="flex items-center gap-4">
				<div class="w-8 h-8 rounded bg-blue-100 flex items-center justify-center">
					<span class="text-sm font-bold text-blue-600">📊</span>
				</div>
				<div>
					<div class="text-sm font-semibold text-gray-900">Client Strategy Deck</div>
					<div class="text-xs text-gray-500">Q3 2024 • 24 slides</div>
				</div>
			</div>
			<div class="flex items-center gap-3">
				<button class="text-gray-400 hover:text-gray-600"><Search size={16} /></button>
				<button class="text-gray-400 hover:text-gray-600"><Bell size={16} /></button>
				<button class="text-gray-400 hover:text-gray-600"><MoreHorizontal size={16} /></button>
			</div>
		</div>

		<div class="flex h-[500px]">
			<!-- Sidebar -->
			<div class="w-64 border-r border-gray-200 bg-gray-50/30 p-4 flex flex-col gap-1">
				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider">Source Materials</div>
				
				<div class="space-y-2 text-xs mb-4">
					<div class="flex items-center gap-2 text-gray-900 bg-white border border-gray-200 p-2 rounded">
						<Database size={14} class="text-blue-500" />
						<span class="truncate">market-research.pdf</span>
					</div>
					
					<div class="flex items-center gap-2 text-gray-900 bg-white border border-gray-200 p-2 rounded">
						<Database size={14} class="text-green-500" />
						<span class="truncate">client-brief.docx</span>
					</div>
					
					<div class="flex items-center gap-2 text-gray-900 bg-white border border-gray-200 p-2 rounded">
						<Database size={14} class="text-purple-500" />
						<span class="truncate">competitor-data.xlsx</span>
					</div>
				</div>

				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider mt-4">Configuration</div>
				<div class="flex items-center gap-2 text-xs text-gray-700 bg-white border border-gray-200 p-2 rounded shadow-sm">
					<div class="w-2 h-2 rounded-full bg-blue-500"></div> Professional Tone
				</div>
			</div>

			<!-- Main Content -->
			<div class="flex-1 bg-white p-6 overflow-y-auto">
				<div class="flex items-center justify-between mb-6">
					<h3 class="text-sm font-semibold text-gray-900 flex items-center gap-2">
						<Activity size={16} /> Generation Progress
					</h3>
					<button class="text-xs text-blue-600 font-medium">+ Add slide</button>
				</div>

				<!-- AI Summary Card -->
				<div class="bg-blue-50/50 border border-blue-100 rounded-lg p-4 mb-8">
					<p class="text-sm text-gray-700 leading-relaxed">
						Generated 24 slides from 3 source documents. All content traced to original sources with citations. Template configured for professional consulting tone.
					</p>
					<div class="flex items-center gap-2 mt-3">
						<div class="w-5 h-5 rounded-full bg-purple-100 flex items-center justify-center text-[10px] text-purple-600">AI</div>
						<span class="text-xs text-gray-500">Processed by Sage AI</span>
					</div>
				</div>

				<!-- Timeline -->
				<div class="relative pl-4 border-l border-gray-200 space-y-8">
					<!-- Event 1 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-green-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Slide 1-5: Executive Summary</div>
								<p class="text-xs text-gray-500 mt-1">Generated from client-brief.docx</p>
							</div>
							<span class="text-xs text-gray-400">Just now</span>
						</div>
					</div>

					<!-- Event 2 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-blue-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Slide 6-15: Market Analysis</div>
								<p class="text-xs text-gray-500 mt-1">Generated from market-research.pdf with CAGR data</p>
							</div>
							<span class="text-xs text-gray-400">2 min ago</span>
						</div>
					</div>
					
					<!-- Event 3 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-purple-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Slide 16-24: Competitive Landscape</div>
								<p class="text-xs text-gray-500 mt-1">Generated from competitor-data.xlsx</p>
							</div>
							<span class="text-xs text-gray-400">5 min ago</span>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
