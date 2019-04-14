# Practica02-Mi-Sitio-Web-css
estilos.css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="../estilos/estilo1.css" type="text/css">
</head>

<body>
    <div id="caja1">
        <header>
            <h1>
                HTML5
            </h1>
            <center>
                <img src="../images/imagen1.jpg" alt="HTML5">
            </center>
        </header>
    </div>
    <div id="caja2">
        <nav>
            <ul>
                <li><a href="pagina1.html"> Tabla</a> </li>
                <li><a href="pagina2.html"> Video</a> </li>
                <li><a href="pagina3.html"> Caracteristicas</a></li>
                <li><a href="pagina4.html"> Beneficios</a> </li>
                <li><a href="pagina5.html"> Ejemplos</a></li>
                <li><a href="formulario.html">Formulario</a></li>
            </ul>
        </nav>
    </div>

    <div id="caja3">
        <section>
            <h2> Que es HTML5?</h2>
            <article>
                <p>
                    HTML5 es un lenguaje markup (de hecho, las siglas de HTML significan Hyper Text Markup Language)
                    usado para estructurar y presentar el contenido para la web. Es uno de los aspectos
                    fundamentales para el funcionamiento de los sitios, pero no es el primero. Es de hecho la quinta
                    revisión del estándar que fue creado en 1990. A fines del año pasado, la W3C la recomendó para
                    transformarse en el estándar a ser usado en el desarrollo de proyectos venideros. Por así decirlo,
                    qué es HTML5 está relacionado también con la entrada en decadencia del viejo estándar HTML 4, que
                    se combinaba con otros lenguajes para producir los sitios que podemos ver hoy en día. Con HTML5,
                    tenemos otras posibilidades para explotar usando menos recursos. Con HTML5, también entra en desuso
                    el formato XHTML, dado que ya no sería necesaria su implementación.
                </p>
            </article>
        </section>

        <section>
            <aside>
                <center>
                    <img src="../images/imagen4.jpg" alt="HTML5">
                </center>
            </aside>

        </section>


        <section>
            <h3>¿CUÁLES SON LAS VERSIONES DE HTML?</h3>
            <article>
                <p>
                    El HTML fue desarrollado originalmente por Tim Bernes-Lee pero debido al rápido crecimiento de la
                    web, surgió la necesidad de crear un estándar para que tanto los programadores como los navegadores
                    pudieran basarse en unas mismas normas para escribir HTML. Cada versión de HTML establece unas
                    normas respecto a cuáles son las etiquetas válidas y cómo se deben escribir.
                    <br /> <br />
                    Los estándares oficiales HTML son el HTML 2.0, el HTML 3.2, el HTML 4.0, el HTML 4.01 y el HTML 5.
                    El HTLM 5 es la última especificación oficial y se espera que continúe evolucionando a lo largo de
                    los próximos años. El XHTML, una forma más avanzada del HTML que se suponía iba a sustituir a éste,
                    podemos considerar que ha quedado integrado dentro del HTML 5.
                </p>
            </article>
        </section>
        <section>
            <article>
                <table border="1">
                    <tr>
                        <td>HTML 2.0 </td>
                        <td> En 1995 se publica el estándar HTML 2.0. A pesar de su nombre, HTML 2.0 es el primer
                            estándar oficial de HTML, es decir, el HTML 1.0 no existió como estándar. HTML 2.0 no
                            soportaba tablas.

                            Se simplificaba al máximo la estructura del documento para agilizar su edición, donde la
                            declaración explícita de los elementos body, html y head es opcional.</td>
                    </tr>
                    <tr>
                        <td>HTML 3.2 </td>
                        <td>La versión HTML 3.2 se publicó en 1997 y es la primera recomendación de HTML publicada por
                            el W3C (Consorcio internacional). Esta revisión incorporó los últimos avances de las páginas
                            web desarrolladas hasta 1996, como applets de Java y texto que fluye alrededor de las
                            imágenes.</td>
                    </tr>
                    <tr>
                        <td>HTML 4.01 </td>
                        <td>La última especificación oficial de HTML se publicó en diciembre de 1999 y se denomina HTML
                            4.01. Desde la publicación de HTML 4.01, el W3C se centró en el desarrollo del estándar
                            XHTML. Por este motivo, en el año 2004, las empresas Apple, Mozilla y Opera mostraron su
                            preocupación por la falta de interés del W3C en HTML y decidieron organizarse en una nueva
                            asociación llamada WHATWG (Web Hypertext Application Technology Working Group) que comenzó
                            el desarrollo del HTML 5, cuyo primer borrador oficial se publicó en enero de 2008. Debido a
                            la fuerza de las empresas que forman el grupo WHATWG y a la publicación de los borradores de
                            HTML 5.0, en marzo de 2007 el W3C decidió retomar la actividad estandarizadora de HTML,
                            dentro del cual decidió integrar el XHTML.</td>
                    </tr>
                    <tr>
                        <td>HTML 5, HTML 5.1, HTML 5.2 </td>
                        <td>El consorcio internacional W3C, después de una evolución de varios años, liberó el HTML 5
                            como estándar oficial a finales de octubre de 2014. HTML 5 incorpora nuevos elementos no
                            contemplandos en HTML 4.01. Hay diversos cambios respecto a HTML 4.01. Hay nuevas etiquetas,
                            se introduce la posibilidad de introducir audio y video de forma directa en la web sin
                            necesidad de plugins o complementos en los navegadores, y otras novedades. El W3C irá
                            lanzando progresivamente nuevas evoluciones del HTML 5.</td>
                    </tr>
                </table>
            </article>
        </section>

        <section>
            <h4>Las nuevas etiquetas</h4>
            <article>
                <p>
                    El lenguaje HTML funciona a través de marcas de sentido llamadas etiquetas. Las etiquetas son la
                    herramienta fundamental para que los navegadores puedan interpretar el código y permitirnos ver
                    imágenes, texto, párrafo, y estructuras. Los navegadores vendrían a ser como “traductores” de las
                    etiquetas, y con HTML5, se agregan nuevas etiquetas para utilizar que nos ahorran el uso de otros
                    productos que se usaban para complementar y hacer cosas que con el simple HTML no se podían hacer.
                    HTML5 fue creado para hacer que el proceso de escribir el código sea más simple y más lógico, por
                    decirlo de una forma. La sintaxis de HTML5 se destaca, como dijimos, en el ámbito multimedia, pero
                    son bastantes las etiquetas introducidas para generar una mejoría.
                    <br />
                    La idea detrás de HTML5 es que podamos visualizar el contenido multimedia variado que podemos
                    encontrar en internet aún cuando nos encontramos en dispositivos de gama baja que no podrían
                    soportarlo cuando tienen que instalar infinidad de plug-ins. No solamente contamos con etiquetas
                    especiales como audio, video y canvas, sino también integración con contenidos de gráficos en
                    vectores (que anteriormente se conocía como la etiqueta object. Con estas etiquetas, los usuarios
                    pueden consumir videos y canciones, por ejemplo, sin necesidad de instalar nada de forma adicional.
                </p>
            </article>
        </section>

        <section>
            <h5>Las más importantes de las nuevas etiquetas creadas son:</h5>
            <article>
                article: esta etiqueta sirve para definir un artículo, un comentario de usuario o una publicación
                independiente dentro del sitio. <br /> <br />
                header, footer: estas etiquetas individuales ahorran tener que insertar IDs para cada uno, como se solía
                hacer anteriormente. Además, se pueden insertar headers y footers para cada sección, en lugar de tener
                que hacerlo únicamente en general. <br /> <br />
                nav: la negación puede ser insertada directamente en el markup, entre estas etiquetas, que nos
                permitirán hacer que nuestras listas oficien de navegación. <br /> <br />
                section: con esta etiqueta, una de las más importantes de las novedades, se puede definir todo tipo de
                secciones dentro de un documento. Por ponerlo de forma sencilla, funciona de una forma similar a la
                etiqueta div que nos separa también diferentes secciones. <br /> <br />
                audio y video: estas son las dos más importantes etiquetas de HTML5, dado que nos permiten acceder de
                forma más simple a contenido multimedia que puede ser reproducido por casi todo tipo de dispositivos;
                marcan el tipo de contenido que estará en su interior. <br /> <br />
                embed: con esta etiqueta se puede marcar la presencia de un contenido interactivo o aplicación externa. <br /> <br />
                canvas: finalmente, esta etiqueta nos permite introducir un “lienzo” dentro de un documento, para poder
                dibujar gráficos por vectores; será necesario el uso de JavaScript.
            </article>
        </section>

    </div>

    <div id="caja4">
        <aside>
            <h3>.......Publicidad.......</h3> <br />
            <img src="../images/imagen2.jpg" alt="Dream soccer league 2018">
        </aside>
        <aside>
            <a href="https://vinkula.com/estructura-del-codigo-html5-anatomia-de-una-pagina-web/">..Ejemplo
                HTML5..</a><br />
            <img src="../images/imagen3.png" alt="Ejemplo HTML5">
        </aside>
    </div>

    <div id="caja5">
        <footer>
            <ul>
                <li>Wilmer John Durazno Zapatanga </li>
                <li>Universidad Politecnica Salesiana </li>
                <li><a href="https://mail.google.com/mail/u/0/?tab=wm#inbox">oscardurasno12@gmail.com</a> </li>
            </ul>
            &copy; Todos los derechos reservados
        </footer>
    </div>
</body>

</html>

codigo para ubiar estilos en el index

* {
    font-family: Arial;
}

body {
    background-image: url(../images/HTML5.jpg);
    background-position: center center;
    background-attachment: fixed;
}

div {
    border-style: none;
    margin: 7px;
    padding: 100px;
}

#caja1 {
    border-color: red;
    background-color: cornflowerblue;
    margin: 2px;
    padding: 2px;
}

#caja2 {
    margin: 0 7px 7px 7px;
    background-color:paleturquoise;
    width: 5%;
    float: left;
    height: 500px;
    border-radius: 98px 98px 98px 98px;
    -moz-border-radius: 98px 98px 98px 98px;
    -webkit-border-radius: 98px 98px 98px 98px;
    border: 9px double #001eff;
}

#caja3 {
    margin: 0 7px 7px 0;
    border-color: darkgray;
    width: 35%;
    float: left;
    height: 2500px;
}

#caja4 {
    margin: 0 0 7px 7px;
    width: 5%;
    float: left;
    height: 500px;
}

#caja5 {
    border: 2px coral dotted;
    margin: 0;
    border-color: darkolivegreen;
    float: left;
    width: 86%;
    height: 10px;
}

h1 {
    text-align: center;
    background-color: firebrick;
}

img {
    width: 301px;
    height: 180px;
}

a {
    background: center;
}
table{
    border: 2px;
    border-color: red;
}
h3{
    color: navy;
    text-align: center;

}
h4{
    color: orangered;
    text-align: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h5{
    color: darkgreen;
    text-align: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
