<script lang="ts">
	import { Mail, Calendar, Database, Activity, Search, Bell, CheckSquare, BarChart2, Zap, MoreHorizontal, Filter, RefreshCw, Plus } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20 text-center">
	<div class="max-w-3xl mx-auto mb-12">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			Build fast. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Forget months of setup. Attio syncs immediately with your email and calendar, building a powerful CRM right before your eyes.</span>
		</h2>
		<button class="mt-8 px-5 py-2.5 bg-black text-white rounded-lg text-sm font-medium hover:bg-gray-800 transition-colors">
			Start for free
		</button>
	</div>

	<!-- Tabs -->
	<div class="flex justify-center gap-4 mb-12">
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-900 shadow-sm hover:bg-gray-50">
			<Mail size={14} /> Email streams
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Calendar size={14} /> Calendar events
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Activity size={14} /> Digital exhaust
		</button>
		<button class="flex items-center gap-2 px-4 py-2 bg-white border border-gray-200 rounded-full text-xs font-medium text-gray-500 hover:text-gray-900 hover:bg-gray-50 transition-colors">
			<Database size={14} /> Data sources
		</button>
	</div>

	<!-- UI Preview -->
	<div class="relative bg-white rounded-xl border border-gray-200 shadow-xl overflow-hidden text-left max-w-5xl mx-auto">
		<!-- Header -->
		<div class="h-14 border-b border-gray-200 flex items-center justify-between px-6 bg-white">
			<div class="flex items-center gap-4">
				<div class="w-8 h-8 rounded-full bg-gray-200 overflow-hidden">
					<img src="https://i.pravatar.cc/150?u=5" alt="Sarah Johnson" class="w-full h-full object-cover"/>
				</div>
				<div>
					<div class="text-sm font-semibold text-gray-900">Sarah Johnson</div>
					<div class="text-xs text-gray-500">Head of IT at GreenLeaf Inc.</div>
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
				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider">Details</div>
				
				<div class="grid grid-cols-[20px_1fr] gap-2 text-xs mb-4">
					<div class="text-gray-400"><Mail size={14} /></div>
					<div class="text-gray-900 truncate">sarah.johnson@greenleaf.com</div>
					
					<div class="text-gray-400"><Calendar size={14} /></div>
					<div class="text-gray-900">Last met 2 days ago</div>
					
					<div class="text-gray-400"><Database size={14} /></div>
					<div class="text-gray-900">GreenLeaf Inc.</div>
				</div>

				<div class="text-[11px] font-medium text-gray-400 mb-2 uppercase tracking-wider mt-4">Lists</div>
				<div class="flex items-center gap-2 text-xs text-gray-700 bg-white border border-gray-200 p-2 rounded shadow-sm">
					<div class="w-2 h-2 rounded-full bg-green-500"></div> Sales Pipeline
				</div>
			</div>

			<!-- Main Content -->
			<div class="flex-1 bg-white p-6 overflow-y-auto">
				<div class="flex items-center justify-between mb-6">
					<h3 class="text-sm font-semibold text-gray-900 flex items-center gap-2">
						<Activity size={16} /> Highlights
					</h3>
					<button class="text-xs text-blue-600 font-medium">+ Add note</button>
				</div>

				<!-- Highlight Card -->
				<div class="bg-blue-50/50 border border-blue-100 rounded-lg p-4 mb-8">
					<p class="text-sm text-gray-700 leading-relaxed">
						Sarah joined the thread "Re: Q3 Roadmap Review". She mentioned they are looking for a new CRM solution and are evaluating competitors.
					</p>
					<div class="flex items-center gap-2 mt-3">
						<div class="w-5 h-5 rounded-full bg-purple-100 flex items-center justify-center text-[10px] text-purple-600">AI</div>
						<span class="text-xs text-gray-500">Summarized by Attio AI</span>
					</div>
				</div>

				<!-- Timeline -->
				<div class="relative pl-4 border-l border-gray-200 space-y-8">
					<!-- Event 1 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-gray-200 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Email sent: "Following up on our chat"</div>
								<p class="text-xs text-gray-500 mt-1">Hey Sarah, great meeting you yesterday. As discussed...</p>
							</div>
							<span class="text-xs text-gray-400">2 days ago</span>
						</div>
					</div>

					<!-- Event 2 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-blue-500 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Meeting: "Intro Call"</div>
								<div class="flex items-center gap-2 mt-1">
									<div class="flex -space-x-1">
										<div class="w-5 h-5 rounded-full bg-gray-200 border border-white"></div>
										<div class="w-5 h-5 rounded-full bg-gray-300 border border-white"></div>
									</div>
									<span class="text-xs text-gray-500">3 attendees</span>
								</div>
							</div>
							<span class="text-xs text-gray-400">3 days ago</span>
						</div>
					</div>
					
					<!-- Event 3 -->
					<div class="relative">
						<div class="absolute -left-[21px] top-0 w-3 h-3 rounded-full bg-gray-200 border-2 border-white"></div>
						<div class="flex items-start justify-between">
							<div>
								<div class="text-sm font-medium text-gray-900">Michael Chang added Sarah to "Sales Pipeline"</div>
							</div>
							<span class="text-xs text-gray-400">5 days ago</span>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
