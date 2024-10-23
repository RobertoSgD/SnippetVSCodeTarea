# SnippetVSCodeTarea
Tarea de SnippetVSCode de Lenguaje de marcas

# README - Snippets de Meta para HTML

Este documento explica los snippets de meta que se utilizan en un documento HTML. Estas etiquetas son esenciales para la optimización de motores de búsqueda (SEO), la accesibilidad y la correcta visualización en diferentes dispositivos.

## Snippets de Meta Google

```html
<meta charset="utf-8">
Descripción: Define la codificación de caracteres del documento como UTF-8, lo que permite el uso de caracteres especiales y es ampliamente recomendado para la mayoría de los sitios web.

<meta name="description" content="Author: A.N. Author, Illustrator: P. Picture, Category: Books, Price: £9.24, Length: 784 pages">
Descripción: Proporciona una breve descripción del contenido de la página. Este texto es frecuentemente utilizado por los motores de búsqueda como el snippet que aparece en los resultados de búsqueda.

<meta name="google-site-verification" content="+nxGUDJ4QpAZ5l9Bsjdi102tLVC21AIh5d1Nl23908vVuFHs34=">
Descripción: Utilizado para verificar la propiedad del sitio web en Google Search Console. Este código ayuda a Google a confirmar que el dueño del sitio es quien dice ser.

<title>Example Books - high-quality used books for children</title>
Descripción: Define el título de la página, que se muestra en la pestaña del navegador y en los resultados de búsqueda. Debe ser conciso y descriptivo.

<meta name="robots" content="noindex,nofollow">
Descripción: Indica a los motores de búsqueda que no deben indexar esta página ni seguir los enlaces que contiene. Útil para páginas que no se desea que aparezcan en los resultados de búsqueda.

<meta name="google" content="nositelinkssearchbox">
Descripción: Instruye a Google para no mostrar un cuadro de búsqueda de enlaces de sitio en los resultados de búsqueda, lo que puede ser útil para mejorar la experiencia del usuario en ciertas páginas.

<meta name="viewport" content="...">
Descripción: Establece las dimensiones y el escalado del área de visualización en dispositivos móviles. Es esencial para hacer que el sitio sea responsivo y accesible en diferentes dispositivos.

<meta name="google-site-verification" content="...">
Descripción: Similar al primer snippet de verificación de Google, este también sirve para confirmar la propiedad del sitio. Asegúrate de que cada propiedad tenga su propio contenido único.

## Snippet de Header

<header>
    <div class="logo">
        <img src="logo.png" alt="Logo">
    </div>
    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#about">Acerca de</a></li>
            <li><a href="#services">Servicios</a></li>
            <li><a href="#contact">Contacto</a></li>
        </ul>
    </nav>
</header>

Descripción: Esta etiqueta define la sección de encabezado del documento. Generalmente contiene el logo y el menú de navegación.

<div class="logo">
Descripción: Un contenedor para el logo del sitio. Utiliza una clase (logo) para facilitar el estilo mediante CSS.

<img src="logo.png" alt="Logo">
Descripción: Una imagen que representa el logo del sitio. El atributo alt proporciona una descripción del logo para mejorar la accesibilidad y SEO.

<nav>
Descripción: Esta etiqueta semántica se utiliza para definir un área de navegación. Ayuda a los motores de búsqueda y a las tecnologías de asistencia a identificar los enlaces de navegación.

<ul>
Descripción: Una lista no ordenada que contiene los elementos del menú de navegación.

<li><a href="#home">Inicio</a></li>
Descripción: Un elemento de lista que incluye un enlace a la sección "Inicio". Los demás elementos de la lista funcionan de manera similar, enlazando a diferentes secciones del sitio.

## Snippet de Footer

```html
<footer>
    <div class="legal">
        <p>&copy; 2024 Tu Empresa. Todos los derechos reservados.</p>
        <ul>
            <li><a href="#privacidad">Política de Privacidad</a></li>
            <li><a href="#terminos">Términos de Servicio</a></li>
            <li><a href="#cookies">Política de Cookies</a></li>
        </ul>
    </div>
    <div class="social">
        <a href="https://facebook.com" target="_blank">Facebook</a>
        <a href="https://twitter.com" target="_blank">Twitter</a>
        <a href="https://instagram.com" target="_blank">Instagram</a>
        <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    </div>
</footer>

<footer>
Descripción: Esta etiqueta define la sección del pie de página del documento. Suele contener información legal y enlaces a otras páginas o redes sociales.

<div class="legal">
Descripción: Un contenedor para la información legal, que a menudo incluye derechos de autor y enlaces a políticas del sitio.

<p>&copy; 2024 Tu Empresa. Todos los derechos reservados.</p>
Descripción: Un párrafo que muestra el aviso de derechos de autor del sitio. Es importante actualizar el año y el nombre de la empresa.

<ul>
Descripción: Una lista no ordenada que contiene enlaces a documentos legales importantes.

<li><a href="#privacidad">Política de Privacidad</a></li>
Descripción: Un elemento de lista que incluye un enlace a la política de privacidad del sitio. Los otros elementos funcionan de manera similar, enlazando a términos de servicio y políticas de cookies.

<div class="social">
Descripción: Un contenedor para los enlaces a redes sociales del sitio.

<a href="https://facebook.com" target="_blank">Facebook</a>
Descripción: Un enlace a la página de Facebook de la empresa. El atributo target="_blank" abre el enlace en una nueva pestaña.




