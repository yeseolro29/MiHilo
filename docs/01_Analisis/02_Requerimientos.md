#REQUERIMIENTOS

I. REQUERIMIENTOS FUNCIONALES //¿que hace el sistema?

## CLIENTE

//AUTENTIFICACIÓN Y CUENTA DEL CLIENTE
1. RF-CLI-01| El cliente podrá registrarse en la plataforma web.
2. RF-CLI-02| El cliente podrá iniciar sesiòn.
3. RF-CLI-03| El cliente podrá cerrar sesiòn.
4. RF-CLI-04| El cliente podrá recuperar su contraseña mediante un código de verificación enviado a su correo electrónico.
5. RF-CLI-05| El cliente podrá consultar sus datos personales.
6. RF-CLI-06| El cliente podrá editar sus datos personales.

//CATÁLOGO Y PRODUCTOS
7. RF-CLI-07| El cliente podrá visualizar los productos disponibles.
8. RF-CLI-08| El cliente podrá consultar el detalle de un producto.
9. RF-CLI-09| El cliente podrá buscar productos por nombre o palabra clave.
10. RF-CLI-10| El cliente podrá filtrar productos por categoría.
    
//COMUNIDAD
11. RF-CLI-11| El cliente podrá visualizar publicaciones de resultados de otras crocheteras.
12. RF-CLI-12| El cliente podrá publicar fotografías de sus proyectos elaborados con los patrones adquiridos.
13. RF-CLI-13| El cliente podrá comentar las publicaciones de otros usuarios.  
    
//TIPS
14. RF-CLI-14| El cliente podrá consultar tips de crochet disponibles en la plataforma.
    
//COMPRAS Y PEDIDOS
15. RF-CLI-15| El cliente podrá comprar productos mediante la plataforma.
16. RF-CLI-16| El cliente podrá consultar su historial de compras.
17. RF-CLI-17| El cliente podrá consultar el estado de sus pedidos.
18. RF-CLI-18| El cliente podrá descargar los patrones digitales adquiridos.
19. RF-CLI-19| El cliente podrá proporcionar una dirección de envío para la compra de amigurumis.

## ADMINISTRADOR

//ADMINISTRACIÓN DE USUARIOS
20. RF-ADM-01| El administrador podrá iniciar sesión en la plataforma.
21. RF-ADM-02| El administrador podrá consultar los usuarios regristrados en la plataforma.
22. RF-ADM-03| El administrador podrá bloquear usuarios.

//ADMINISTRACION DE PRODUCTOS 
23. RF-ADM-04| El administrador podrá registrar nuevos productos en la plataforma. 
24. RF-ADM-05| El administrador podrá editar la información de los productos.
25.  RF-ADM-06| El administrador podrá eliminar o desactivar productos. 
26.  RF-ADM-07| El administrador podrá modificar los precios de los productos.
27.  RF-ADM-08| El administrador podrá gestionar las categorías de productos.
28.  RF-ADM-09| EEl administrador podrá gestionar el inventario de los amigurumis disponibles.  

//ADMINISTRACÓN DE CONTENIDO
29. RF-ADM-10| El administrador podrá publicar tips de crochet.
30. RF-ADM-11| El administrador podrá editar los tips de crochet publicados.
31. RF-ADM-12| El administrador podrá eliminar los tips de crochet publicados. 
32. RF-ADM-13| EEl administrador podrá gestionar las publicaciones destacadas de los clientes.
    
//MODERACIÓN DE COMUNIDAD
33. RF-ADM-14| El administrador podrá gestionar los comentarios realizados por los usuarios. 
34. RF-ADM-15| El administrador podrá gestionar las publicaciones de resultados realizadas por los clientes. 
35. RF-ADM-16| El administrador podrá consultar el historial de compras realizadas.
36. RF-ADM-17| El administrador podrá validar los pagos realizados mediante transferencia o depósito.
37. RF-ADM-18| El administrador podrá habilitar el acceso a los patrones digitales una vez confirmado el pago.
38. RF-ADM-19| El administrador podrá consultar el estado de los pedidos de amigurumis.

//REPORTES
39. RF-ADM-20| El administrador podrá consultar reportes de ventas.




II. REQUERIMIENTOS NO FUNCIONALES //Calidad del sistema o sus procesos

1. RNF-01-SEGURIDAD | Las contraseñas deberán almacenarser de forma cifrada. 
2. RNF-02-RENDIMIENTO | Las páginas deberán cargar en menos de 3 segundos con una conexion estable.
3. RNF-03-COMPATIBILIDAD | El sistema deberán ser compatible con Google Chrome, Microsoft Edge, Mozilla Firefox.
4. RNF-04-RESPONSIVE | La interfaz deberá adaptarse correctamente a dispositivos móviles, tabletas y computadoras.
5. RNF-05-DISPONIBILIDAD | El sistema deberá estar disponible las 24 horas.
6. RNF-06-BASE DE DATOS | El sistema deberá utilizar SQL Server para el almacenamiento y gestión de la información.
7. RNF-07-TECNOLOGÍA | El sistema será desarrollado utilizando ASP.NET Core MVC y Entity Framework Core.
  