<script lang="ts">
	export let href: string;

	import { page } from '$app/stores';
</script>

<a {href}>
	<div class={`flex items-center gap-1 ${$page.url.pathname === href ? 'text-blue-500' : ''}`}>
		<slot />
	</div>
</a>
