<script>
	import HeaderSpacer from '../components/HeaderSpacer.svelte';
</script>

<div id="about" class="h-screen flex flex-col">
	<HeaderSpacer />
	<div class="border-blue-200 border rounded p-4 m-4 flex-grow">
		<div class="flex items-start flex-col gap-3">
			<div class="flex items-center gap-3">
				<img class="rounded-full w-24" src="/basile.jpg" alt="profile" />
				<div>
					<h2 class="text-lg font-semibold">
						Basile Spaenlehauer <span class="font-normal">aka</span>
						<span
							class="font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-500 to-blue-500"
							>spaenleh</span
						>
					</h2>
					<p>Software Engineer - MSc in Electrical Engineering</p>
					<q class="text-gray-500">I like to build things, and make them look good when I can</q>
				</div>
			</div>
			<div class="flex gap-4 flex-col">
				<div>
					<h3 class="font-bold">Experience</h3>
					<p>
						I have worked on <em>frontend</em> and <em>fullstack</em> projects in personal and professional
						settings.
					</p>
					<p>
						My current occupation is at <a class="underline text-blue-700" href="https://graasp.org"
							>Graasp</a
						>
						building a digital education platform.
					</p>
				</div>
				<div>
					<h3 class="font-bold">Hobbies</h3>
					<p>
						During my free time I enjoy learning about new technologies. Here are some of the
						subjects I like to explore:
					</p>
					<ul class="list-disc list-inside">
						<li>Home servers</li>
						<li>Functional programming languages: <a href="https://glem.run">Gleam</a></li>
					</ul>
					<p>
						When I am not at the computer I like to ride my bike and read books. I also enjoy
						cooking for others, because it brings m joy to share good food.
					</p>
				</div>
			</div>
		</div>
	</div>
</div>
