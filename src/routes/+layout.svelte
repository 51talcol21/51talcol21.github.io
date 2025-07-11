<script lang="ts">
	import '../app.css';
	import { base } from '$app/paths';
	import { page } from '$app/state';
	
	const headerClass: string = "hover:text-yellow-500 hover:transition-colors transition duration-300 border-b-2 border-b-transparent ease-in-out hover:border-b-black hover:border-b-2";
	const activeClass: string = "text-green-500 border-b-green-500 border-b-2";
	
	let { children } = $props();
</script>

<nav class="flex flex-row gap-2 justify-center my-8">
    <a href="{base}/" class={page.url.pathname === "/" ? activeClass : headerClass}>Home</a> - 
    <a href="{base}/about" class={page.url.pathname === "/about" ? activeClass : headerClass}>About</a> - 
	<a href="{base}/projects" class={page.url.pathname === "/projects" ? activeClass : headerClass}>Projects</a>
</nav>

<hr class="h-px my-8 bg-gray-200 border-0 dark:bg-gray-700">

{@render children()}
