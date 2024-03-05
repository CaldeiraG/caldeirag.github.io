<script lang="ts">
	import '../app.pcss';
	import { ModeWatcher } from "mode-watcher";
	import DarkModeToggle from '$lib/components/DarkModeToggle.svelte';
</script>

<ModeWatcher />
<div class="relative flex flex-col p-5">
	<div class="flex md:flex md:flex-grow flex-row justify-end space-x-5 items-center">
		<h1>About Me</h1>
		<h1>Portfolio</h1>
		<DarkModeToggle/>
	</div>
	<div class="mt-8 md:mt-12">
		<slot />
	</div>
</div>
