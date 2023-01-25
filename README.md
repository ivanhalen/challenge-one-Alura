<!DOCTYPE html>

<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viwport" content="width=device-width">
        <link rel="stylesheet" href="style.css">
        <link rel="stelesheet" href="reset.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap">
    </head>

    <body>
        <header>
            <img src="imagenes/Logo.png" alt="logo alura">
        </header>
        <main>
            
            <section class="seccion1">
                <textarea class="area" placeholder="Ingrese el texto aqui"></textarea>
                <div class="contenedorS"><img src="imagenes/Vector.png" alt="simbolo afirmacion"><p>Solo letras minúsculas y sin acentos.</p></div> 
                <div class="contenedor-botones">                                                                 
                    <input type="button" class="btn-encriptar" value="Encriptar">
                    <input type="button" class="btn-desencriptar" value="Desencriptar">


                </div>
                

            </section>
            <section class="seccion2">
                <div class="contenedor-munieco">
                    <img src="imagenes/Muneco.png" alt="nino alura">                    
                </div>
                <div class="contenedor-h3">
                    <h3>Ningún mensaje fue encontrado.</h3>
                </div>
                <div class="contenedor-parrafo">
                    <p>Ingresa el texto que deseas encriptar o desencriptar</p>
                </div>

                <div class="contenedor-resultado">
                    <h3>Mensaje encriptado</h3>
                    <p class="texto-resultado"></p>

                </div>
                <div class="contenedor-copiar">
                    <input type="button" class="btn-copiar" value="Copiar">

                </div>                
       
                   
            </section>
        </main>
        <footer>
            <p class="copyright">&copy copyright Alura - 2023</p>

        </footer>
        <script src="script.js"></script>
    </body>
</html>
