<script>
    import AreaLateral from "./AreaLateral.svelte";
    import Cabecalho from "./cabecalho.svelte";
    import Rodape from "./Rodape.svelte";


</script>
<div class="flex flex-col min-h-screen bg-black text-white">
<Cabecalho/>
<div class="flex-1 flex max-w-7x1 mx-auto w-full p-5">
    <main class="flex-1 ">
        <slot></slot>
    </main>
    <AreaLateral/>

</div>

<Rodape/>
</div>