# Tema 3. Sistema de Control de versiones
> Práctica 7. Trabajo colaborativo usando Pull Requests

> En esta práctica se usará el MISMO repositorio (empresa-web)

### CONCEPTOS CLAVE

Un Pull Request es una solicitud para integrar cambios a main
En lugar de hacer merge directamente:
- El desarrollador propone cambios
- El líder revisa
- El líder aprueba e integra

### ORGANIZACIÓN DEL EQUIPO

| Rol  | Responsabilidad |
|------|-----------------|
|Líder | Revisa y aprueba Pull Requests |
| Dev 1 | Modifica Home |
|Dev 2| Modifica Nosotros |
| Dev 3 | Modifica Servicios |

Todos trabajan con ramas

### ESCENARIO DE TRABAJO

Ahora el sitio ya existe, pero la empresa solicita mejoras:
- Agregar contenido nuevo
- Mejorar diseño de cada página
- Agregar secciones o cambiar imágenes, etc.

## PARTE 1: Preparación

Todos actualizan su repositorio
git checkout main
git pull

Crear nueva rama
Cada alumno crea una nueva rama:
git checkout -b feature-mejora-nombre

### Ejemplos:

- feature-mejora-home
- feature-mejora-nosotros
- feature-mejora-servicios

## PARTE 2: Realizar cambios

Modificar archivos
Cada alumno mejora su página:

Ejemplo:
``` html
<h2>Nueva sección agregada</h2>
<p>Contenido adicional</p>
```

> Nota: Cada integrante debe realmente agregar o modificar algo del diseño de la página que le corresponde.

Guardar cambios
``` git
git add .
git commit -m "Se agrega mejora a la página "
``` 

Subir rama
``` git
git push -u origin feature-mejora-nombre
```

## PARTE 3: Crear Pull Request

Ir a GitHub

Cada alumno debe:
- Entrar al repositorio
- Ver mensaje: "Compare & pull request"
- Hacer clic

### Configurar Pull Request
Completar:
- Título: Mejora en página Home
- Descripción: Se agregó nueva sección informativa

### Crear Pull Request

Clic en:
Create pull request

¿Qué acaba de pasar?
El alumno NO integró cambios
Solo solicitó al líder que los revise

PARTE 4: Revisión del líder

El líder revisa los PR
El líder entra a:
pestaña Pull Requests


Revisar cambios
Puede ver:
- Archivos modificados
- Líneas agregadas

## Aprobar Pull Request
Clic en:
Merge pull request
## Luego:
Confirm merge

## IMPORTANTE
El líder repite esto con TODOS los PR del equipo

PARTE 5: Sincronización final

Todos actualizan proyecto
git checkout main
git pull
