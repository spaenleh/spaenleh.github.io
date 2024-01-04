<div id="home" class="flex flex-col items-center justify-around h-screen">
	<p>
		Hi, I am <span
			class="font-mono font-extrabold text-3xl text-transparent bg-clip-text bg-gradient-to-r from-cyan-500 to-blue-500"
			>spaenleh</span
		>,
		<br />
		welcome.
	</p>
	<button
		class="group hover:bg-slate-50 transition-all duration-500 p-3 rounded-xl"
		on:click={() => document.getElementById('about')?.scrollIntoView({ behavior: 'smooth' })}
	>
		<div class="flex flex-col items-center">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				stroke-width="1"
				stroke="currentColor"
				class="w-12 h-12 animate-bounce"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					d="M9 12.75l3 3m0 0l3-3m-3 3v-7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
				/>
			</svg>
			<span class="opacity-0 group-hover:opacity-100 duration-700">Check me out !</span>
		</div>
	</button>
</div>
