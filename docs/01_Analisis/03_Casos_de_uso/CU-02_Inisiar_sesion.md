# CU-02 | Iniciar sesión

| Campo | Descripción | 
|--------|-------------|
| Código | CU-02 |
| Nombre | Iniciar sesión |
| Objetivo | Permitir al cliente acceder a la plataforma mediante sus credenciales para utilizar las funciones de acuerdo a su rol|
| Actor principal | Cliente o Admistrador |
| Actores secundarios | Sistema |
| Requerimiento relacionado | RF-CLI-02|
| Prioridad | Alta |
| Frecuencia | Frecuente |
| Precondiciones | El cliente debe de estar registrado y debe de contar con credenciales validas|

## Postcondiciones 
- El cliente ha iniciado sesión correctamente Postcondiciones
- El sistema crea una sesión activa para el usuario



## Flujo principal

| Paso | Acción |
|------|--------|
| 1 | El cliente o administrador selecciona la opción **Iniciar sesión**. |
| 2 | El sistema muestra el formulario de autenticación |
| 3 | El cliente o administrador ingresa su correo electrónico y contraseña |
| 4 | El sistema valida las credenciales. |
| 5 | El sistema concede el acceso |
|  | Si el usario es cliente el sistema muestra la página de catálogo, compras, publicaciones de otras clientas |
|  | Si el usario es administrador el sistema muestra el panel de administración|

## Flujos alternativos

| Código | Descripción |
|---------|-------------|
| FA-01 | El correo o contraseña son incorrectas|

## Excepciones

| Código | Descripción |
|---------|-------------|
| EX-01 | El servidor no está disponible. |
| EX-02 | No es posible establecer conexión con la base de datos |
