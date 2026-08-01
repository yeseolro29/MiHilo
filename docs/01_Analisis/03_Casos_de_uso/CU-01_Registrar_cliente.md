# CU-01 | Registrar cliente

| Campo | Descripción | 
|--------|-------------|
| Código | CU-01 |
| Nombre | Registrar cliente |
| Objetivo | Permitir que un cliente se registre en la plataforma. |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-01 |
| Prioridad | Alta |
| Frecuencia | Ocasional |
| Precondiciones | El cliente no debe estar registrado. |
| Postcondiciones | El cliente queda registrado en el sistema. |


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción **Registrarse**. |
| 2 | El sistema muestra el formulario de registro. |
| 3 | El cliente captura sus datos personales. |
| 4 | El cliente confirma el registro. |
| 5 | El sistema valida la información. |
| 6 | El sistema guarda los datos del cliente. |
| 7 | El sistema muestra un mensaje de registro exitoso. |

## Flujos alternativos

| Código | Descripción |
|---------|-------------|
| FA-01 | El correo ya existe. El sistema solicita otro correo. |
| FA-02 | Hay campos obligatorios vacíos. El sistema muestra un mensaje de validación. |

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | Error al guardar la información en la base de datos. |
| EX-02 | El servidor no está disponible. |