<script lang="ts">
	import { X } from 'lucide-svelte';
</script>

<div class="fixed top-0 left-0 right-0 z-50">
	<!-- Top Banner -->
	<div class="bg-black text-white text-xs font-medium py-2.5 px-4 relative">
		<div class="flex justify-center items-center gap-2">
			<span>Meet the Attio Developer Platform</span>
			<span class="opacity-70">→</span>
		</div>
		<button class="absolute right-4 top-1/2 -translate-y-1/2 text-white/60 hover:text-white">
			<X size={14} />
		</button>
	</div>

	<!-- Main Nav -->
	<nav class="bg-white/90 backdrop-blur-md border-b border-gray-200">
		<div class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
			<div class="flex items-center gap-8">
				<a href="/" class="flex items-center gap-2 text-black hover:opacity-80 transition-opacity">
					<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path d="M5.5 12L10.5 19L15.5 12L10.5 5L5.5 12Z" fill="black"/>
						<path d="M10.5 19L15.5 12L20.5 19H10.5Z" fill="black" fill-opacity="0.5"/>
						<path d="M5.5 12L10.5 5L15.5 12H5.5Z" fill="black" fill-opacity="0.5"/>
					</svg>
					<span class="font-bold text-xl tracking-tight">attio</span>
				</a>

				<div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
					<button class="hover:text-black flex items-center gap-1">
						Platform <span class="text-[10px]">▼</span>
					</button>
					<button class="hover:text-black flex items-center gap-1">
						Resources <span class="text-[10px]">▼</span>
					</button>
					<a href="#" class="hover:text-black">Customers</a>
					<a href="#" class="hover:text-black">Pricing</a>
				</div>
			</div>

			<div class="flex items-center gap-4">
				<a href="#" class="text-sm font-medium text-gray-600 hover:text-black">Sign in</a>
				<a href="#" class="bg-black text-white text-sm font-medium px-4 py-2 rounded-lg hover:bg-gray-800 transition-colors">
					Start for free
				</a>
			</div>
		</div>
	</nav>
</div>
