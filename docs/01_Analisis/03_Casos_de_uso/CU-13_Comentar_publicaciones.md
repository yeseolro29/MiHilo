# CU-13 | Comentar publicaciones de otras crocheteras

| Campo | Descripción | 
|--------|-------------|
| Código | CU-13 |
| Nombre | Comentar publicaciones de otras crocheteras |
| Objetivo | Permitir al cliente comentar las publicaciones de resultados de otras crocheteras|
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-13 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la plataforma
-El cliente debe haber iniciado sesión.
-Debe existir al menos una publicación disponible.

## Postcondiciones

-El comentario del cliente ha sido registrado correctamente.
-El comentario se muestra en la publicación correspondiente.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción Resultados de crochet. |
| 2 | El sistema muestra las publicaciones de otras crocheteras. |
| 3 | El cliente selecciona la publicación de su interés. |
| 4 | El sistema muestra la publicación y la opción para agregar un comentario. |
| 5 | El cliente escribe su comentario y selecciona Publicar. |
| 6 | El sistema valida el comentario. |
| 7 | El sistema guarda el comentario y lo muestra en la publicación correspondiente. |


## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 | No existen publicaciones disponibles. El sistema muestra un mensaje indicando que actualmente no hay publicaciones en la plataforma. |
| FA-02 | El comentario está vacío o no cumple con las reglas establecidas. El sistema solicita al cliente corregirlo antes de publicarlo. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible comentar publicaciones en este momento.|


 
