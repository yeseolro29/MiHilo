# CU-06 | Editar datos personales

| Campo | Descripción | 
|--------|-------------|
| Código | CU-06 |
| Nombre | Editar datos personales |
| Objetivo | Permitir al cliente actualizar la información de su perfil para mantener sus datos personales actualizados |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-06 |
| Prioridad | Alta |
| Frecuencia | Ocasional |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma 

## Postcondiciones 
-Los datos del cliente han sido actualizados correctamente.
-La información modificada queda almacenada en la base de datos. 


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente accede a la configuración de su cuenta |
| 2 | El sistema muestra la información registrada del cliente | 
| 3 | El cliente modifica los datos que desea actualizar |
| 4 | El cliente selecciona la opción de guarda los cambios |
| 5 | El sistema valida la información ingresada. 
| 6 | El sistema actualiza los datos y confirma que la operación fue existosa | 

## Flujos alternativos 

-FA-01 El cliente ingresa información inválida o deja campos obligatorios vacíos. El sistema muestra un mensaje indicado los datos que deben corregirse. 

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no esposible guardar los cambios realizados.|


 
