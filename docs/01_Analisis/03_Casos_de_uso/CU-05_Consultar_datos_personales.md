# CU-05 | Visualizar datos personales

| Campo | Descripción | 
|--------|-------------|
| Código | CU-05 |
| Nombre | Visualizar datos personales |
| Objetivo | Permitir al cliente consultar la información de su perfil registrada en la plataforma |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-05 |
| Prioridad | Alta |
| Frecuencia | Ocasional |

## Precondiciones
-El cliente debe de tener una cuenta registrada en la paltaforma
-El cliente debe haber iniciado sesión

## Postcondiciones

-El cliente visualiza correctamente la información de su perfil.
-No se realizan modificaciones a los datos almacenados.


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente accede a la configuración de su cuenta |
| 2 | El sistema recupera la información registrada del cliente | 
| 3 | El sistema muestralos datos personales del cliente |

## Flujo alternativo
| Código | Descripción |
|------|--------|
| FA-01 | La información del perfil no puede recuperarse correctamente. El sistema informa al cliente e invita a intentarlo nuevamente |

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no esposible mostrar la información del perfil en este momento.|


 
