# CU-07 | Visualizar productos disponibles

| Campo | Descripción | 
|--------|-------------|
| Código | CU-07 |
| Nombre | Visualizar productos disponibles|
| Objetivo | Permitir al cliente consultar los productos disponibles en la plataforma |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-07 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma
-El cliente debe haber iniciado sesión 

## Postcondiciones

-El catálogo de productos es mostrado al cliente.
-El cliente puede seleccionar un producto para consultar su información o iniciar su proceso de compra. 


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente accede con su cuenta a la plataforma |
| 2 | El sistema valida las credenciales del cliente | 
| 3 | El sistema muestra la página principal |
| 4 | El cliente selecciona la opción de Catálogo |
| 5 | El sistema muestra el catálogo con los productos disponibles |


## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 | No existen productos disponibles. El sistema muestra un mensaje indicando que actualmente no hay productos en el catálogo. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible mostrar el catálogo en este momento.|


 
