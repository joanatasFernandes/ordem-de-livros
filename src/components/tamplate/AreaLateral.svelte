<script>
    import Menu from "./Menu.svelte";
    import MenuItem from "./MenuItem.svelte";

</script>
<aside class="flex flex-col self-start border rounded-md border-zinc-800  p-5 gap-10 w-72">

    <Menu Titulo = "Navegação">
        <MenuItem texto = "Inicio" href="/"/>
        <MenuItem texto = "Personagens" href="/personagens"/>
        <MenuItem texto = "Autores" href="/autores"/>
        <MenuItem texto = "Séries" href="/"/>
    </Menu>

    <Menu Titulo = "Principais Autores">
        <MenuItem texto = "J.K Rowling" href="/"/>
        <MenuItem texto = "J.R.R Tolkien" href="/"/>
        <MenuItem texto = "Jeorge R.R Martin" href="/autores/george-martin"/>
    </Menu>

    <Menu Titulo = "Outras Categorias">
       <MenuItem texto = "Ultimas Noticias"/>
       <MenuItem texto = "Séries Populares"/>
       <MenuItem texto = "FaceBook"/>
       <MenuItem texto = "Instagram"/>
       <MenuItem texto = "Youtube"/>
    </Menu>
</aside>