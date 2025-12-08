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
						<path d="M5.5 12L10.5 19L15.5 12L10.5 5L5.5 12Z" fill="white"/>
						<path d="M10.5 19L15.5 12L20.5 19H10.5Z" fill="white" fill-opacity="0.5"/>
						<path d="M5.5 12L10.5 5L15.5 12H5.5Z" fill="white" fill-opacity="0.5"/>
					</svg>
					<span class="font-bold text-xl tracking-tight">attio</span>
				</a>
			</div>

			<!-- Columns -->
			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Platform</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Refer a team <span class="bg-blue-600 text-[10px] px-1.5 py-0.5 rounded ml-1 text-white">New</span></a></li>
					<li><a href="#" class="hover:text-white">Changelog</a></li>
					<li><a href="#" class="hover:text-white">Gmail extension ></a></li>
					<li><a href="#" class="hover:text-white">iOS app ></a></li>
					<li><a href="#" class="hover:text-white">Android app ></a></li>
					<li><a href="#" class="hover:text-white">Security</a></li>
				</ul>
				
				<h4 class="text-sm font-medium text-gray-400 mt-8 mb-4">Company</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Customers</a></li>
					<li><a href="#" class="hover:text-white">Announcements</a></li>
					<li><a href="#" class="hover:text-white">Engineering blog <span class="bg-blue-600 text-[10px] px-1.5 py-0.5 rounded ml-1 text-white">New</span></a></li>
					<li><a href="#" class="hover:text-white">Careers</a></li>
					<li><a href="#" class="hover:text-white">Manifesto</a></li>
					<li><a href="#" class="hover:text-white">Become a partner</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Import from</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Salesforce</a></li>
					<li><a href="#" class="hover:text-white">Hubspot</a></li>
					<li><a href="#" class="hover:text-white">Pipedrive</a></li>
					<li><a href="#" class="hover:text-white">Zoho</a></li>
					<li><a href="#" class="hover:text-white">Excel</a></li>
					<li><a href="#" class="hover:text-white">CSV</a></li>
				</ul>

				<h4 class="text-sm font-medium text-gray-400 mt-8 mb-4">Attio for</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Startups</a></li>
					<li><a href="#" class="hover:text-white">Deal flow</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Apps</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Gmail</a></li>
					<li><a href="#" class="hover:text-white">Outlook</a></li>
					<li><a href="#" class="hover:text-white">Segment</a></li>
					<li><a href="#" class="hover:text-white">Mailchimp</a></li>
					<li><a href="#" class="hover:text-white">Slack</a></li>
					<li><a href="#" class="hover:text-white">Outreach</a></li>
					<li><a href="#" class="hover:text-white">Mixmax</a></li>
					<li><a href="#" class="hover:text-white">Typeform</a></li>
					<li><a href="#" class="hover:text-white">Zapier</a></li>
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
