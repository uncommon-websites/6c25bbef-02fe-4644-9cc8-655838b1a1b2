<script lang="ts">
	import { ArrowRight, Zap, Bot, Database, BarChart3, Mail, MessageSquare, Calendar, CheckCircle2, Search, Plus, MoreHorizontal } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="mb-20 max-w-2xl">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			GTM at full throttle. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Execute your revenue strategy with precision. Design powerful workflows, deploy AI, integrate your data and build detailed reports — all in one platform.</span>
		</h2>
	</div>

	<div class="border border-gray-200 rounded-xl overflow-hidden bg-white shadow-sm">
		<!-- Row 1: Automate everything -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Automate everything</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						You're in control. Automate even the most complex business processes with our powerful, intelligent automation engine.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore automations <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center overflow-hidden relative">
				<!-- Workflow Diagram Mockup -->
				<div class="relative w-full max-w-lg">
					<!-- Trigger -->
					<div class="absolute top-0 left-0 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-64 z-10">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<Zap size={12} /> Trigger
						</div>
						<div class="text-sm font-medium text-gray-900">When Deal updated</div>
						<div class="text-xs text-gray-400 mt-1">Trigger when primary contact is updated</div>
					</div>

					<!-- Path -->
					<svg class="absolute top-16 left-32 w-full h-40 pointer-events-none" style="z-index: 0;">
						<path d="M 0 0 V 20 H 100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
						<path d="M 0 0 V 20 H -100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
					</svg>

					<!-- Branch 1 -->
					<div class="absolute top-32 -left-20 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<div class="w-2 h-2 rounded-full bg-blue-500"></div> Switch
						</div>
						<div class="text-sm font-medium text-gray-900">Health score</div>
						<div class="mt-2 flex gap-2">
							<span class="px-2 py-0.5 bg-green-100 text-green-700 text-[10px] rounded">Good</span>
							<span class="px-2 py-0.5 bg-red-100 text-red-700 text-[10px] rounded">Poor</span>
						</div>
					</div>

					<!-- Branch 2 -->
					<div class="absolute top-32 left-40 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<Mail size={12} /> Email
						</div>
						<div class="text-sm font-medium text-gray-900">Onboarding manual</div>
						<div class="flex items-center gap-2 mt-2">
							<div class="w-6 h-6 rounded-full bg-gray-100 flex items-center justify-center text-[10px]">JD</div>
							<span class="text-xs text-gray-500">Sent from John Doe</span>
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

		<!-- Row 2: Deploy AI -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Deploy AI</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Put our research agent to work and rotate complex tasks that normally require human effort, like prospecting, lead routing and more.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore AI <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="bg-white rounded-xl shadow-sm border border-gray-200 w-full max-w-md overflow-hidden">
					<div class="p-3 border-b border-gray-100 flex items-center gap-2 bg-gray-50/50">
						<Bot size={16} class="text-purple-600" />
						<span class="text-xs font-medium text-gray-700">New task found</span>
					</div>
					<div class="p-4 space-y-4">
						<div class="flex gap-3">
							<div class="w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center flex-shrink-0">
								<Bot size={16} class="text-purple-600" />
							</div>
							<div class="flex-1">
								<div class="bg-gray-50 rounded-lg p-3 text-sm text-gray-800 mb-2">
									<p class="font-medium mb-1">Activate PLG motion</p>
									<p class="text-gray-500 text-xs">Does the company sell software to other businesses?</p>
								</div>
								
								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 mb-2 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<div class="w-4 h-4 rounded bg-blue-100 flex items-center justify-center text-[10px] text-blue-600">✓</div>
										<span class="font-medium">Conduct role of subjectivity?</span>
									</div>
									<p class="text-gray-500 text-xs">Yes the company was only found recently.</p>
								</div>

								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<div class="w-4 h-4 rounded bg-blue-100 flex items-center justify-center text-[10px] text-blue-600">✓</div>
										<span class="font-medium">Identify key stakeholders</span>
									</div>
									<p class="text-gray-500 text-xs">Who are the key stakeholders at the company?</p>
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

		<!-- Row 3: Connect any type of data -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Connect any type of data</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Sync product data, billing data, and everything in between, for a real-time single source of truth for your business.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore data <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="relative w-full max-w-md h-64 flex items-center justify-center">
					<!-- Center Logo -->
					<div class="w-16 h-16 bg-black rounded-xl flex items-center justify-center z-10 shadow-lg">
						<span class="text-white font-bold text-2xl font-serif">a</span>
					</div>

					<!-- Connecting Lines -->
					<svg class="absolute inset-0 w-full h-full pointer-events-none">
						<line x1="50%" y1="50%" x2="20%" y2="20%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="80%" y2="20%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="20%" y2="80%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="80%" y2="80%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="50%" y2="15%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="50%" y2="85%" stroke="#e5e7eb" stroke-width="1" />
					</svg>

					<!-- Icons -->
					<div class="absolute top-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Database size={20} class="text-blue-500" />
					</div>
					<div class="absolute top-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<MessageSquare size={20} class="text-green-500" />
					</div>
					<div class="absolute bottom-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Mail size={20} class="text-red-500" />
					</div>
					<div class="absolute bottom-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Calendar size={20} class="text-purple-500" />
					</div>
					<div class="absolute top-4 left-1/2 -translate-x-1/2 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<div class="w-5 h-5 bg-orange-500 rounded-full"></div>
					</div>
					<div class="absolute bottom-4 left-1/2 -translate-x-1/2 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<div class="w-5 h-5 bg-indigo-500 rounded-sm"></div>
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

		<!-- Row 4: Powerful reporting -->
		<div class="grid grid-cols-1 md:grid-cols-3">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Powerful reporting</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Create real-time, detailed reports that scale with your data. Visualize, customize, and get deep insights in seconds — not hours.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore reporting <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="grid grid-cols-2 gap-6 w-full max-w-lg">
					<!-- Chart 1 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="flex items-center justify-between mb-4">
							<div class="text-xs font-medium text-gray-500">Revenue</div>
							<MoreHorizontal size={14} class="text-gray-400" />
						</div>
						<div class="h-32 flex items-end gap-2 justify-between px-2">
							<div class="w-full bg-pink-100 h-[40%] rounded-t-sm"></div>
							<div class="w-full bg-pink-200 h-[60%] rounded-t-sm"></div>
							<div class="w-full bg-pink-300 h-[30%] rounded-t-sm"></div>
							<div class="w-full bg-pink-400 h-[80%] rounded-t-sm"></div>
							<div class="w-full bg-pink-500 h-[50%] rounded-t-sm"></div>
						</div>
						<div class="flex justify-between mt-2 text-[10px] text-gray-400">
							<span>Mon</span>
							<span>Tue</span>
							<span>Wed</span>
							<span>Thu</span>
							<span>Fri</span>
						</div>
					</div>

					<!-- List -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm space-y-3">
						<div class="flex items-center justify-between mb-2">
							<div class="text-xs font-medium text-gray-500">Top Deals</div>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-green-500"></div>
							<span class="flex-1">Acme Corp</span>
							<span class="font-medium">$12k</span>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-blue-500"></div>
							<span class="flex-1">Global Inc</span>
							<span class="font-medium">$8.5k</span>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-purple-500"></div>
							<span class="flex-1">Stark Ind</span>
							<span class="font-medium">$15k</span>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-orange-500"></div>
							<span class="flex-1">Wayne Ent</span>
							<span class="font-medium">$22k</span>
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
