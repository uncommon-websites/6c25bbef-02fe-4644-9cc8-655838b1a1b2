<script lang="ts">
	import { Twitter, Linkedin, Github, Youtube } from 'lucide-svelte';
</script>

<footer class="bg-black text-white pt-20 pb-10 px-6">
	<div class="max-w-[1200px] mx-auto">
		<div class="grid grid-cols-2 md:grid-cols-6 gap-10 mb-20">
			<!-- Logo Column -->
			<div class="col-span-2">
				<a href="/" class="flex items-center gap-2 text-white mb-6">
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
						<rect x="4" y="4" width="16" height="16" rx="2" stroke="white" stroke-width="2" fill="none"/>
						<path d="M4 9 L20 9 M9 4 L9 20" stroke="white" stroke-width="2"/>
					</svg>
					<span class="font-bold text-xl tracking-tight">Sage</span>
				</a>
			</div>

			<!-- Columns -->
			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Product</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Templates <span class="bg-blue-600 text-[10px] px-1.5 py-0.5 rounded ml-1 text-white">New</span></a></li>
					<li><a href="#" class="hover:text-white">Marketplace</a></li>
					<li><a href="#" class="hover:text-white">Precision Editing</a></li>
					<li><a href="#" class="hover:text-white">Mind Map</a></li>
					<li><a href="#" class="hover:text-white">Export</a></li>
					<li><a href="#" class="hover:text-white">Pricing</a></li>
				</ul>
				
				<h4 class="text-sm font-medium text-gray-400 mt-8 mb-4">Company</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">About</a></li>
					<li><a href="#" class="hover:text-white">Blog</a></li>
					<li><a href="#" class="hover:text-white">Careers <span class="bg-blue-600 text-[10px] px-1.5 py-0.5 rounded ml-1 text-white">We're hiring</span></a></li>
					<li><a href="#" class="hover:text-white">Fundraising</a></li>
					<li><a href="#" class="hover:text-white">Contact</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Use Cases</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Consulting</a></li>
					<li><a href="#" class="hover:text-white">Sales</a></li>
					<li><a href="#" class="hover:text-white">Fundraising</a></li>
					<li><a href="#" class="hover:text-white">Marketing</a></li>
					<li><a href="#" class="hover:text-white">Product</a></li>
					<li><a href="#" class="hover:text-white">Strategy</a></li>
				</ul>

				<h4 class="text-sm font-medium text-gray-400 mt-8 mb-4">Sage for</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Consultants</a></li>
					<li><a href="#" class="hover:text-white">Entrepreneurs</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Integrations</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">PowerPoint</a></li>
					<li><a href="#" class="hover:text-white">Google Slides</a></li>
					<li><a href="#" class="hover:text-white">Keynote</a></li>
					<li><a href="#" class="hover:text-white">Figma</a></li>
					<li><a href="#" class="hover:text-white">Notion</a></li>
					<li><a href="#" class="hover:text-white">Google Drive</a></li>
					<li><a href="#" class="hover:text-white">Dropbox</a></li>
					<li><a href="#" class="hover:text-white">Slack</a></li>
					<li><a href="#" class="hover:text-white">API</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Resources</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Startup program</a></li>
					<li><a href="#" class="hover:text-white">Help center</a></li>
					<li><a href="#" class="hover:text-white">Automation templates</a></li>
					<li><a href="#" class="hover:text-white">Developers ></a></li>
					<li><a href="#" class="hover:text-white">System status ></a></li>
					<li><a href="#" class="hover:text-white">Hire an expert</a></li>
					<li><a href="#" class="hover:text-white">Downloads</a></li>
				</ul>
			</div>
		</div>

		<div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row items-center justify-between gap-4">
			<div class="flex items-center gap-6">
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Linkedin size={20} /></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Twitter size={20} /></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><div class="w-5 h-5 border border-current rounded-sm flex items-center justify-center text-[10px] font-bold">X</div></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Youtube size={20} /></a>
			</div>
			
			<div class="flex items-center gap-6 text-xs text-gray-500">
				<span>© 2025 Attio Ltd. All rights reserved.</span>
				<a href="#" class="hover:text-gray-300">Terms & Conditions</a>
				<a href="#" class="hover:text-gray-300">Privacy Policy</a>
				<a href="#" class="hover:text-gray-300">LLMs</a>
			</div>
		</div>
	</div>
</footer>
