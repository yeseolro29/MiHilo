# CU-11 | Visualizar resultados de otras crocheteras

| Campo | Descripción | 
|--------|-------------|
| Código | CU-11 |
| Nombre | Visualizar resultados de otras crocheteras |
| Objetivo | Permitir al cliente consultar resultados de otras crocheteras. |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-11 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones

-El cliente debe tener una cuenta registrada en la plataforma.
-El cliente debe haber iniciado sesión.

## Postcondiciones

-El cliente puede visualizar las publicaciones de resultados de otras crocheteras.
-El cliente puede consultar la información de una publicación seleccionada.

## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción **Resultados de crochet**. |
| 2 | El sistema muestra las publicaciones de otras crocheteras. |
| 3 | El cliente selecciona una publicación de su interés. |
| 4 | El sistema muestra la información de la publicación seleccionada. |

## Flujo alternativo

| Código | Descripción |
|---------|-------------|
| FA-01 | No existen publicaciones disponibles. El sistema muestra un mensaje indicando que actualmente no hay publicaciones en la plataforma. |

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible mostrar el apartado de publicaciones en este momento. |