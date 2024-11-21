<script>
    export let Titulo = "Navegação";
</script>

<div class="flex flex-col gap-3">
    <span class="tex-sm font-bold text-zinc-500">{Titulo}</span> 
    <ul class="flex flex-col"> 
    <slot></slot>
    </ul>
</div>