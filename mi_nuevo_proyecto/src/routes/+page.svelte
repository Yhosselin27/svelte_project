<script>

    import MiComponente from "./MiComponente.svelte";
</script>

<div>
    <h1>Este es el título</h1>
</div>

<h2>
    <span>
        Hay países con muchos colores
    </span>
    
</h2>

<p>Colombia es un país con mucha diversidad y muchos colores</p>

<MiComponente color = "azul"/>

<a href="/quienes_somos">Ir a información</a>

<style>
    h1{
        margin: 0 auto;
        color: red;
    }
    span{
        color: rgb(42, 165, 83);
    }
</style>