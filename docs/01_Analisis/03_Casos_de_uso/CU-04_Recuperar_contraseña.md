# CU-04 | Recuperar contraseña

| Campo | Descripción | 
|--------|-------------|
| Código | CU-04 |
| Nombre | Recuperar contraseña |
| Objetivo | Permitir al cliente recuperar el acceso a su cuenta mediante un proceso de verificación de identidad |
| Actor principal | Cliente |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-04 |
| Prioridad | Alta |
| Frecuencia | Ocasional |
| Precondiciones | El cliente debe de tener una cuenta registrada en la paltaforma |

## Postcondiciones 
-La contraseña del cliente ha sido actualizado correctamente.
-El cliente puede iniciar sesión con la  nueva contraseña. 


## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente selecciona la opción **¿Olvidaste tu contraseña?** en la pantalla de inicio de sesión |
| 2 | El sistema solicita el correo electrónico registrado |
| 3 | El cliente ingresa su correo electrónico  |
| 4 | El sistema verifica el correo electrónico exista | 
| 5 | El sistema envía un código o enlace de recuperación al correo electronico registrado |
| 6 | El cliente ingresa el código o accede al enlace recibido |
| 7 | El sistema permite registrar una nueva contraseña |
| 8 | El sistema confirma que la contraseña fue localizada correctamente |


## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible y no esposible completar el proceso de recuperación en este momento. Intente nuevamente mas tarde.|


## Reglas de negoci
-RN-01 El código de recuperación tendra una vigencia de 10 min. 
-RN-02 El código de recuperación solo podrá utilizarse una vez.
-RN-03 Después de 5 intentos fallidos, el código quedará invalido y el cliente deberá solicitar unos nuevo. 
