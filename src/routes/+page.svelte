<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="relative h-full isolate overflow-hidden bg-gradient-to-r from-[#1D267D] via-gray-[#0C134F] to-[#1D267D] text-white py-24 sm:py-32 my-5 mx-5 rounded-lg">
		
		<div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl" aria-hidden="true">
		  <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
		</div>
		<div class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu" aria-hidden="true">
		  <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
		</div>
		<div class="mx-auto max-w-7xl px-6 lg:px-8">
		  <div class="mx-auto max-w-2xl lg:mx-0">
			<h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Work with us</h2>
			<p class="mt-6 text-lg leading-8 text-gray-300">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
		  </div>
		  <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
			<div class="grid grid-cols-1 gap-x-8 gap-y-6 text-base font-semibold leading-7 text-white sm:grid-cols-2 md:flex lg:gap-x-10">
			  <a href="#sell">Start a Company <span aria-hidden="true">&rarr;</span></a>
			  <a href="#contributions">Full Time Support <span aria-hidden="true">&rarr;</span></a>
			  <a href="#pitches">Pitches <span aria-hidden="true">&rarr;</span></a>
			  <a href="#contacts">Meet our leadership <span aria-hidden="true">&rarr;</span></a>
			</div>
			<dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
			  <div class="flex flex-col-reverse">
				<dt class="text-base leading-7 text-gray-300">Total Companies</dt>
				<dd class="text-2xl font-bold leading-9 tracking-tight text-white">12</dd>
			  </div>
			  <div class="flex flex-col-reverse">
				<dt class="text-base leading-7 text-gray-300">Full-time Support</dt>
				<dd class="text-2xl font-bold leading-9 tracking-tight text-white">300+</dd>
			  </div>
			  <div class="flex flex-col-reverse">
				<dt class="text-base leading-7 text-gray-300">Pitches per week</dt>
				<dd class="text-2xl font-bold leading-9 tracking-tight text-white">40</dd>
			  </div>
			  <div class="flex flex-col-reverse">
				<dt class="text-base leading-7 text-gray-300">Investing Opportunites</dt>
				<dd class="text-2xl font-bold leading-9 tracking-tight text-white">Unlimited</dd>
			  </div>
			</dl>
		  </div>
		</div>
	  </div>
	  <div class="bg-[#010836] relative px-5 py-10 lg:px-20 md:px-10 sm:px-5 lg:py-10 ">
		<div class=" ">
			<div class="text-[#D4ADFC]  font-bold text-xl" id="sell">Sell</div>
			<h2 class="mt-5 text-[42px] text-white ">
				Nodes and relayers for all your favourite protocols
			</h2>
			
		</div>
		<div class="mt-10 md:mt-30  ">
			<div class="text-[#D4ADFC] mt-10 text-xl font-bold" id="pitches">Pitches</div>
			<h2 class="mt-10 text-[42px] text-white ">
				The platform for running resiliant pitches
			</h2>
			<p class="mt-10 text-2xl  text-white">
				We’ve built the leading platform for those who want to participate on new chains. <br />
				Our engineering, protocol and security teams have built a premier protocol agnostic <br />
				platform. Our platform removes the difficulty often associated with running node
			</p>
		</div>
		<div class="mt-10 md:mt-30   ">
			<div class="text-[#D4ADFC] mt-10 text-xl font-bold" id="contributions">About</div>
			<h2 class="mt-10 text-[42px] text-white ">Governance and Development</h2>
			<p class="mt-10 text-2xl  text-white">
				We participate in governance across all active networks to ensure the interests <br />
				of the community are fairly represented. Additionally, we are regular code contributors <br />
				to these networks too.
			</p>
		</div>
		<div class="my-10 md:my-30 ">
			<div class="text-[#D4ADFC] mt-10 text-xl" id="contacts">Contact</div>
			<div class="flex mt-10 justify-between">
				<h2 class=" text-3xl text-white font-bold ">Contact us today</h2>
				<button class="bg-[#0C134F] w-[207px] rounded=[4px] h-[54px] md:h-50 text-[#D4ADFC] text-xl  px-2 py-2">
					Get In Touch
				</button>
			</div>
		</div>
	</div>
</section>

<style lang="postcss">
	 :global(html) {
    background-color: theme(colors.gray.100);
  }
	
</style>
