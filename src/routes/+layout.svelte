<script lang="ts">
	import '../app.css';
    import Logo from '../components/tamplate/logo.svelte';
	let { children } = $props();
</script>

<div class="flex flex-col flex justify-center items-center gap-5
bg-black text-white min-h-screen">
<Logo />
{@render children()}
</div>

