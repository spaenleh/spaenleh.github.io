<script>
	import '../app.css';
	import HomeIcon from '../icons/home-icon.svelte';
	import AboutIcon from '../icons/about-icon.svelte';
	import NavLink from '../components/nav-link.svelte';
	import ProjectsIcon from '../icons/projects-icon.svelte';

	let y = 0;
	const SCROLL_MARGIN = 24;
</script>

<svelte:window bind:scrollY={y} />
<div
	class={`${
		y < SCROLL_MARGIN ? 'opacity-0' : 'opacity-100'
	} hover:opacity-100 bg-white z-50 fixed top-0 left-4 right-4 transition-all duration-500 border-b`}
>
	<nav class="flex items-center gap-2 justify-center m-2">
		<NavLink href="#home">
			<HomeIcon />
			<span>Home</span>
		</NavLink>
		<NavLink href="#about">
			<AboutIcon />
			<span>About</span>
		</NavLink>
		<NavLink href="#projects">
			<ProjectsIcon />
			<span>Projects</span>
		</NavLink>
	</nav>
</div>
<slot />
