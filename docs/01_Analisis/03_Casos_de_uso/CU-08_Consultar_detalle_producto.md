# CU-08 | Consultar el detalle de un producto

| Campo | Descripción | 
|--------|-------------|
| Código | CU-08 |
| Nombre | Consultar el detalle de un producto |
| Objetivo | Permitir al cliente consultar los detalles de los productos |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-08 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma
-El cliente debe haber iniciado sesión.


## Postcondiciones
-El cliente visualiza la información detallada del producto seleccionado.
-El cliente puede consultar las características del producto.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción de catálogo |
| 2 | El sistema muestralos los productos disponibles | 
| 3 | El cliente selecciona el producto de su interés |
| 4 | El sistema muestra los detalles del producto seleccionado |
| 5 | El cliente consulta la información del producto |


## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 |  No existen productos disponibles. El sistema muestra un mensaje indicando que actualmente no hay productos en el catálogo. |

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible mostrar los datalles del producto en este momento.|

## Detalles que se mostrara en cada producto

//PATRÓN DIGITAL
-NombreNombre
-Descripción
-Imagen
-Precio
-Categoría
-Nivel de dificultad
-Formato del archivo
-Materiales necesarios

//AMIGURUMI
-Nombre
-Descripción
-Imagen
-Precio
-Categoría
-Tamaño
-Material
-Disponibilidad/stock