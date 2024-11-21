<script lang="ts">
	import '../app.css';
    import Logo from '../components/tamplate/logo.svelte';
    import Pagina from '../components/tamplate/pagina.svelte';
	let { children } = $props();
</script>

<Pagina>
	{@render children()}
</Pagina>


