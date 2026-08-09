# CU-14 | Consultar tips de crochet

| Campo | Descripción | 
|--------|-------------|
| Código | CU-14 |
| Nombre | Consultar tips de crochet |
| Objetivo | Permitir al cliente consultar tips de crochet disponibles en la plataforma |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-14 |
| Prioridad | Alta |
| Frecuencia | Frecuente |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la plataforma
-El cliente debe haber iniciado sesión 

## Postcondiciones

- El cliente puede visualizar los tips de crochet disponibles.
- El cliente puede consultar la información del tip seleccionado. 


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción **Tips de crochet**. |
| 2 | El sistema muestra la lista de tips de crochet disponibles. |
| 3 | El cliente selecciona un tip de su interés. |
| 4 | El sistema muestra la información completa del tip seleccionado. |


## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 | No existen tips disponibles. El sistema muestra un mensaje indicando que actualmente no hay tips en la plataforma. |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible mostrar el apartado de tips de crochet en este momento.|