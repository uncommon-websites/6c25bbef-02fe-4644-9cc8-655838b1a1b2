<script lang="ts">
	import { User, Briefcase, Building2, Plus, MoreHorizontal } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="text-center max-w-3xl mx-auto mb-20">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			A seismic shift in CRM flexibility. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Attio's powerful data model adapts to how your business works, not the other way around. Your business model — perfectly reflected in your CRM.</span>
		</h2>
		<button class="mt-8 px-4 py-2 bg-white border border-gray-200 rounded-full text-sm font-medium hover:border-gray-300 transition-colors">
			Explore our data model
		</button>
	</div>

	<!-- Data Model Visual -->
	<div class="relative bg-gray-50/50 rounded-xl p-10 md:p-20 border border-gray-100 overflow-hidden">
		<!-- Background Grid -->
		<div class="absolute inset-0" style="background-image: radial-gradient(#e5e7eb 1px, transparent 1px); background-size: 20px 20px; opacity: 0.5;"></div>

		<!-- Top Filters -->
		<div class="flex justify-center gap-2 mb-16 relative z-10">
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Scale-ups</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">SaaS startups</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">SMBs</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Investors</button>
		</div>

		<!-- Objects Diagram -->
		<div class="relative max-w-4xl mx-auto h-[500px]">
			<!-- Connecting Lines (SVG) -->
			<svg class="absolute inset-0 w-full h-full pointer-events-none z-0">
				<!-- User to Person -->
				<path d="M 200 150 C 200 200, 250 250, 300 300" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
				<!-- Person to Deal -->
				<path d="M 450 300 C 500 250, 550 200, 600 150" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
				<!-- Person to Add Object -->
				<path d="M 450 350 C 500 350, 550 350, 600 350" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
			</svg>

			<!-- User Object -->
			<div class="absolute top-10 left-10 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-green-100 flex items-center justify-center text-green-600">
							<User size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">User</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">Standard</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">#</div>
						<span>User ID</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">@</div>
						<span>Engagement score</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>User type</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 4 More Attributes</div>
				</div>
			</div>

			<!-- Deal Object -->
			<div class="absolute top-10 right-10 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-purple-100 flex items-center justify-center text-purple-600">
							<Briefcase size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">Deal</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">Standard</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>Deal name</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">□</div>
						<span>Workspace</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">≡</div>
						<span>Stage</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 2 More Attributes</div>
				</div>
			</div>

			<!-- Person Object (Center) -->
			<div class="absolute top-60 left-1/2 -translate-x-full -ml-4 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-blue-100 flex items-center justify-center text-blue-600">
							<User size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">Person</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">Standard</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>Name</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">@</div>
						<span>Email</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">🏢</div>
						<span>Company</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 12 More Attributes</div>
				</div>
			</div>

			<!-- Add Object (Placeholder) -->
			<div class="absolute top-60 left-1/2 ml-4 w-64 h-40 border-2 border-dashed border-blue-200 rounded-lg flex items-center justify-center bg-blue-50/30 z-10">
				<div class="flex items-center gap-2 text-blue-500 font-medium text-sm">
					<Plus size={16} /> Add object
				</div>
			</div>
		</div>

		<!-- Table View at Bottom -->
		<div class="mt-10 bg-white border border-gray-200 rounded-lg shadow-sm overflow-hidden max-w-4xl mx-auto">
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-100 bg-gray-50 text-[11px] font-medium text-gray-500">
				<div class="flex items-center gap-2"><User size={12} /> User</div>
				<div class="flex items-center gap-2"><div class="w-3 h-3 flex items-center justify-center">#</div> User ID</div>
				<div class="flex items-center gap-2"><div class="w-3 h-3 flex items-center justify-center">Aa</div> User type</div>
				<div class="flex items-center gap-2"><div class="w-3 h-3 flex items-center justify-center">@</div> Engagement score</div>
			</div>
			<!-- Row 1 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=1" alt="" class="w-full h-full object-cover"/></div> Albert Lund</div>
				<div class="font-mono text-gray-500 text-[10px]">6s59-027f-4C54-98a3-3</div>
				<div><span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded text-[10px]">Member</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Light</span></div>
			</div>
			<!-- Row 2 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=2" alt="" class="w-full h-full object-cover"/></div> Jenna Roberts</div>
				<div class="font-mono text-gray-500 text-[10px]">2d77-027f-5823-96V9-3</div>
				<div><span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded text-[10px]">Admin</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Light</span></div>
			</div>
			<!-- Row 3 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=3" alt="" class="w-full h-full object-cover"/></div> David Chen</div>
				<div class="font-mono text-gray-500 text-[10px]">16j0-d76d-5090-ab709-5</div>
				<div><span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded text-[10px]">Admin</span></div>
				<div><span class="text-purple-600 underline decoration-purple-200">Power User</span></div>
			</div>
			<!-- Row 4 -->
			<div class="grid grid-cols-4 gap-4 p-3 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=4" alt="" class="w-full h-full object-cover"/></div> Marc Lopez</div>
				<div class="font-mono text-gray-500 text-[10px]">9bc0-3abd-8990-dj36-7t</div>
				<div><span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded text-[10px]">Member</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Inactive</span></div>
			</div>
		</div>
	</div>
</section>
