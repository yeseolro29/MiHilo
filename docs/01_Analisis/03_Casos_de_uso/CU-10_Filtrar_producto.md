# CU-10 | Filtrar productos por categoría 

| Campo | Descripción | 
|--------|-------------|
| Código | CU-10 |
| Nombre | Filtrar productos por categoría  |
| Objetivo | Permitir al cliente filtrar los productos por categoría |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-10 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma
-El cliente debe haber iniciado sesión.


## Postcondiciones
-El sistema muestra los productos que coinciden con la categoría seleccionada.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción de catálogo |
| 2 | El sistema muestralos los productos disponibles | 
| 3 | El cliente selecciona una categoría |
| 4 | El sistema procesa el filtro seleccionado |
| 5 | El sistema muestra los productos que coinciden con la categoría seleccionada |


## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 |  No existen productos disponibles. El sistema muestra un mensaje indicando que actualmente no hay productos en el catálogo. |
| FA-02 |  No existen productos que coincidan con categoría seleccionada. El sistema muestra un mensaje indicando que no se encontraron resultados. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible filtrar los productos en este momento |