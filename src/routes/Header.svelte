<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	import github from '$lib/images/github.svg';
</script>


	<!-- <div class="corner">
		<a href="https://kit.svelte.dev">
			<img src={logo} alt="SvelteKit" />
		</a>
	</div>

	<nav>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L1,2 C1.5,3 1.5,3 2,3 L2,0 Z" />
		</svg>
		<ul>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
				<a href="/about">About</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/sverdle') ? 'page' : undefined}>
				<a href="/sverdle">Sverdle</a>
			</li>
		</ul>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
		</svg>
	</nav>

	<div class="corner">
		<a href="https://github.com/sveltejs/kit">
			<img src={github} alt="GitHub" />
		</a>
	</div> -->
	<header class=" bg-gradient-to-r from-[#1D267D] via-gray-[#0C134F] to-[#1D267D] text-white rounded-lg">
		<nav class="mx-auto flex max-w-7xl items-center justify-between p-6 lg:px-8" aria-label="Global">
		  <div class="flex lg:flex-1">
			<a href="#" class="-m-1.5 p-1.5">
			  <span class="sr-only">Your Company</span>
			  <h1 class="text-white text-2xl font-bold">Your Company</h1>
			</a>
		  </div>
		  <div class="flex lg:hidden">
			<button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-white">
			  <span class="sr-only">Open main menu</span>
			  <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
			  </svg>
			</button>
		  </div>
		  <div class="hidden lg:flex lg:gap-x-12">
			<a href="#sell" class="text-sm font-semibold leading-6 text-white">Sell</a>
			<a href="#pitches" class="text-sm font-semibold leading-6 text-white">Pitches</a>
			<a href="#contributions" class="text-sm font-semibold leading-6 text-white">About</a>
			<a href="#contacts" class="text-sm font-semibold leading-6 text-white">Company</a>
		  </div>
		  <div class="hidden lg:flex lg:flex-1 lg:justify-end">
			<a href="/login" class="text-sm font-semibold leading-6 text-white">Log in <span aria-hidden="true">&rarr;</span></a>
		  </div>
		</nav>
		<!-- Mobile menu, show/hide based on menu open state. -->
		<div class="lg:hidden" role="dialog" aria-modal="true">
		  <!-- Background backdrop, show/hide based on slide-over state. -->
		  <div class="fixed inset-0 z-10"></div>
		  <div class="fixed inset-y-0 right-0 z-10 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
			<div class="flex items-center justify-between">
			  <a href="#" class="-m-1.5 p-1.5">
				<span class="sr-only">Your Company</span>
				<img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt="">
			  </a>
			  <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700">
				<span class="sr-only">Close menu</span>
				<svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
				  <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
				</svg>
			  </button>
			</div>
			<div class="mt-6 flow-root">
			  <div class="-my-6 divide-y divide-gray-500/10">
				<div class="space-y-2 py-6">
				  <a href="#sell" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-white hover:bg-gray-50">Sell</a>
				  <a href="#pitches" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-white hover:bg-gray-50">Features</a>
				  <a href="#contributions" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-white hover:bg-gray-50">Marketplace</a>
				  <a href="#contacts" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-white hover:bg-gray-50">Company</a>
				</div>
				<div class="py-6">
				  <a href="#" class="-mx-3 block rounded-lg px-3 py-2.5 text-base font-semibold leading-7 text-white hover:bg-gray-50">Log in</a>
				</div>
			  </div>
			</div>
		  </div>
		</div>
	  </header>
<style>
	
</style>
