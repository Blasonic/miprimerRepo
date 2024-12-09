<script>
    const marcas = [
        { name: 'LOUIS VUITTON', img: 'imagenes/louis_vuitton.png' },
        { name: 'GUCCI', img: 'imagenes/gucci.png' },
        { name: 'NIKE', img: 'imagenes/nike.png' },
    ];
</script>

<section class="marcas">
    {#each marcas as marca}
        <div class="marca">
            <img src={marca.img} alt={marca.name} />
            <p>{marca.name}</p>
        </div>
    {/each}
</section>

<style>
    .marcas {
        text-align: center;
        padding: 40px 0;
    }
    .marca {
        display: inline-block;
        margin: 15px;
        text-align: center;
    }
    .marca img {
        width: 200px;
        height: auto;
        margin-inline: 85px;
        margin-top: 20px;
    }
    .marca p {
        margin-top: 10px;
        font-weight: bold;
        color: #8a2b2b;
    }
</style>


