# CU-03 | Cerrar sesión

| Campo | Descripción | 
|--------|-------------|
| Código | CU-03 |
| Nombre | Cerrar sesión |
| Objetivo | Permitir al usuario finalizar su sesión de manera segura. finalizando el acceso a la plataforma|
| Actor principal | Usuario |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-03 |
| Prioridad | Alta |
| Frecuencia | Frecuente |
| Precondiciones | El usuario debe de tener una sesión activa en la plataforma|

## Postcondiciones 
- La sesión del usuario ha finalizadocorrectamente 
- El sistema elimina la sesión inactiva 
- El usuario es redirigido a la página de inicio



## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente o administrador selecciona la opción **Cerrar sesión**. |
| 2 | El cliente o administrador seleccionan la opción que desean |
| 3 | El sistema valida la opción. |
| 4 | El sistema permanece en la plataforma o finaliza la sesión |



## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no es posible cerrar la sesión en este momento |
