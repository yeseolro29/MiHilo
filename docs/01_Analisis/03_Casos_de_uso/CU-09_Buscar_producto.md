# CU-09 | Buscar productos por nombre o palabra clave

| Campo | Descripción | 
|--------|-------------|
| Código | CU-09 |
| Nombre | Buscar productos por nombre o palabra clave  |
| Objetivo | Permitir al cliente buscar productos por el nombre o palabra clave |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-09 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma
-El cliente debe haber iniciado sesión.


## Postcondiciones
-El sistema muestra los productos que coinciden con el nombre o palabra clave ingresada por el cliente.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción de catálogo |
| 2 | El sistema muestralos los productos disponibles | 
| 3 | El cliente ingresa el nombre o palabra clave del producto que desea buscar |
| 4 | El sistema procesa la búsqueda |
| 5 | El sistema muestra los productos que coinciden con los criterios de búsqueda |

## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 |  No existen productos disponibles. El sistema muestra un mensaje indicando que actualmente no hay productos en el catálogo. |
| FA-02 |  No existen productos que coincidan con el nombre o palabra clave ingresada. El sistema muestra un mensaje indicando que no se encontraron resultados. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible mostrar los productos en este momento.|