<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="flex flex-col flex justify-center items-center gap-5
bg-black text-white min-h-screen">
{@render children()}
</div>

