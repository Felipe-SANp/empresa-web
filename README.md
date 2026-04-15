
# SMARTPARK 
### Autores

- Felipe Santiago (index.html) (Lider + Desarrollador):
- Carlos Adrian (Nosotros.html) (Desarrollador):
- Ruben Omar (Servicios.html) (Desarrollador):
- Jesus Damian (Contacto.html) (Desarrollador):


## Cómo contribuir

Este repositorio contiene una plantilla HTML base que usan las páginas del sitio: `index.html`, `servicios.html`, `nosotros.html` y `contacto.html`.

Objetivo
- Permitir que cualquier colaborador agregue contenido a las páginas sin romper la plantilla general.

Guía rápida para contribuir
- Usa únicamente HTML5 semántico (etiquetas como `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `h1..h6`, `p`, `ul`, `ol`, etc.).
- No es necesario añadir CSS: el proyecto incluye PicoCSS vía CDN, que ya aplica estilos basados en las etiquetas HTML. Documentación de PicoCSS: https://picocss.com/docs
- Para casos excepcionales donde necesites estilos adicionales, usa `styles.css` (ya enlazado en todas las páginas). Evita modificar las reglas globales que afecten a otras páginas.

Buenas prácticas
- No modifiques el `header` ni el `footer` (contienen la navegación y la marca). Añade o edita contenido dentro de la etiqueta `main` o dentro de secciones específicas que hayas creado.
- Mantén la estructura semántica y accesible: agrega `aria-label` o `role` cuando tenga sentido.
- Mantén fragmentos de contenido autónomos: evita estilos en línea y scripts que alteren la plantilla global.

Ejemplo mínimo (en `main`):

``` html
<main>
	<section>
		<h2>Título de sección</h2>
		<p>Parrafo descriptivo. Añade más secciones si es necesario.</p>
		<ul>
			<li>Punto 1</li>
			<li>Punto 2</li>
		</ul>
	</section>
</main>
```

Comprobación antes de enviar PR
- Revisa que los enlaces en la navegación sigan apuntando a `index.html`, `servicios.html`, `nosotros.html` y `contacto.html`.
- Abre las páginas localmente en el navegador para comprobar que el contenido se muestra correctamente con el estilo de PicoCSS.

Contacto y dudas
- Si tienes dudas sobre estructura o accesibilidad, abre un issue o comenta tu PR para revisión.

Gracias por contribuir.

