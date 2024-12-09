<script>
    const ofertas = [
        { name: 'ADIDAS', img: 'imagenes/adidas.png' },
        { name: 'NIKE', img: 'imagenes/esponja.png' },
        { name: 'EMPORIO ARMANI', img: 'imagenes/armani.png' }
    ];
</script>

<section class="ofertas">
    <h2>OFERTAS</h2>
    {#each ofertas as oferta}
        <div class="oferta">
            <img src={oferta.img} alt={oferta.name} />
            <p>{oferta.name}</p>
        </div>
    {/each}
</section>

<style>
    .ofertas {
        text-align: center;
        padding: 40px 0;
    }
    .ofertas h2 {
        color: #8a2b2b;
        margin-bottom: 20px;
    }
    .oferta {
        display: inline-block;
        margin: 15px;
        text-align: center;
    }
    .oferta img {
        width: 200px;
        height: auto;
        margin-inline: 85px;
    }
    .oferta p {
        margin-top: 10px;
        font-weight: bold;
        color: #8a2b2b;
    }
</style>

