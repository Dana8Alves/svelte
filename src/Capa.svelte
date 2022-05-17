<script>
    import CaixaDeIcones from "./CaixaDeIcones.svelte";
</script>

<div class="fundo">
    <div class = "centro">
        <img src="./img/foto.png" alt="Foto de Dana" class="foto"/>
        <h1 class="titulo">Dana Alves</h1>
        <h2 class="descricao">Entrepreneur</h2>
        <CaixaDeIcones />
    </div>
</div>

<style>
    .fundo{
        width: 100%;
        min-height: 100vh;
        background-color: #660033;
        
    }

    .centro{
        color: white;
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
    }

    .foto {
        border-radius: 50%;
        width: 250px;
    }
</style>

