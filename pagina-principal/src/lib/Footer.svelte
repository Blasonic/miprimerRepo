<footer>
    <div class="contenido-footer">
        <div class="enlaces-footer">
            <a href="">Sobre Nosotros</a>
            <a href="">Ayuda</a>
            <a href="">Colaboraciones</a>
            <a href="">Tienda</a>
            <a href="">Contacto</a>
        </div>
        <div class="ponerCorreo">
            <p>No te pierdas ninguna de nuestras ofertas</p>
            <input type="email" placeholder="Correo">
            <button>Enviar</button>
        </div>
        <div class="legal-footer">
        <a href="#">Aviso Legal</a>
        <a href="#">Política de cookies</a>
    <div class="redes-sociales">
            <a href="#"><img src="imagenes/instagram.png" alt="Instagram"></a>
            <a href="#"><img src="imagenes/facebook.png" alt="Facebook"></a>
            <a href="#"><img src="imagenes/twitter.png" alt="Twitter"></a>
        </div>    
    </div> 
     
    </div>
</footer>
<style>
    footer {
        background-color: #f4f4f4;
        padding: 20px;
        text-align: center;
    }
    .contenido-footer {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        padding-bottom: 20px;
        border-bottom: 1px solid #ddd;
    }
    .enlaces-footer a, .legal-footer a {
        display: block;
        margin: 5px 0;
        color: #8a2b2b;
        text-decoration: none;
        margin-bottom: 30px;
        align-items: center;
    }
    .ponerCorreo p {
        font-weight: bold;
        color: #8a2b2b;
        align-items: center;
    }
    .ponerCorreo input {
        padding: 5px;
        width: 80%;
        margin-right: 5px;
        border: 1px solid #ddd;
    }
    .redes-sociales a {
     display: flex;
     display: inline;
    gap: 10px;
    margin-top: 30px;
       
    }
    .redes-sociales img {
        width: 40px;
        height: 33px;
    }
</style>


