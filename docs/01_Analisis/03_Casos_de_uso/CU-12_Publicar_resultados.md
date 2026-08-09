# CU-12 | Publicar fotografías de los resultados

| Campo | Descripción | 
|--------|-------------|
| Código | CU-12 |
| Nombre | Publicar fotografías de los resultados |
| Objetivo | Permitir al cliente publicar fotografíasde sus proyectos elaborados con los patrones adquiridos. |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-12 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones

-El cliente debe tener una cuenta registrada en la plataforma.
-El cliente debe haber iniciado sesión.
-El cliente debe haber adquirido al menos un patrón digital.

## Postcondiciones

-El publicación del cliente ha sido publicada correctamente.
-La publicación se muestra en el apartado de resultados de crochet.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción **Resultados de crochet**. |
| 2 | El sistema muestra la publicaciones disponibles. |
| 3 | El cliente selecciona el opción para realizar una publicación. |
| 4 | El sistema muestra el formulario para realizar la publicación. |
| 5 | El cliente selecciona la fotografía de su proyecto. |
| 6 | El cliente agrega una descripción de la publicación, si lo considera necesario. |
| 7 | El cliente selecciona la opción **Publicar**. |
| 8 | El sistema valida la información proporcionada. |
| 9 | El sistema registra y muestra la publicación en el apartado de resultados de crochet. |



## Flujo alternativo

| Código | Descripción |
|---------|-------------|
| FA-01 | La fotografía no cumple con los requisitos establecidos. El sistema muestra un mensaje indicando que el archivo no puede ser publicado. |
| FA-02 | El cliente intenta publicar sin seleccionar una fotografía. El sistema solicita seleccionar una imagen antes de continuar. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible realizar publicaciones en este momento. |
| EX-02 | No es posible guardar la publicación debido a un error en la base de datos. |