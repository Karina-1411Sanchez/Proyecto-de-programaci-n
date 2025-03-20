Titulo del proyecto
-
SISTEMA DE MONITOREO PARA CULTIVOS DE PAPA.

DESCRIPCION:
El sistema de monitoreo de cultivos es una aplicacion web accesible para los agricultores de papa, que les permite gestionar los cultivos.
La plataforma permitira registrar la fecha de siembra para emepezar a monitorear el estado del cultivo desde cero, ademas podran reportar 
problemas que lo afecten mediante imagenes detalladas y recibiran notificaciones sobre fertilizacion oportuna.

Objetivo del proyecto
-

Desarrollar una aplicación web accesible e intuitiva que permita a los agricultores de papa gestionar y monitorear sus cultivos, recordandoles
la fertilizacion opurtuna para prevenir enfermedades  plagas que l puedan afectar 



Modulos del sistema
- 
1. Autenticación y gestion de usuarios:

este modulo que permite el acceso seguro al sistema mediante inicio de sesion, una vez autenticados podran acceder a las funcionalidades del sistema 
y gestionar sus cultivos.
 
   
2. Gestión y seguimiento del cultivo:

El modulo se encarga de que el usuario ingrese datos del cultivo desde cero como la feca de siembra y subir imagenes detalladas de la evolucion del
cultivo para monitorearlo.


3. Reporte de problemas:

Reportar problemas con imagenes y descripcion detallada.

4. Notificaciones y alertas:

enviara notificaciones de alerta y recordatorio sobre fecha de fertilizacion oportuna.

5. Interfaz de usuario:
   
Es la interfaz visual que permite a los agricultores interactuar con el sistema y acceder a todos los modulos.

Flujo del sistema 
-
1. autenticacion y gestión de usuarios:

Registro de ususarios nuevos:El usuario accede al sistema se encuentra con la pagina de registro, ingresa datos como correo electronico y contraseña 
el sistema valida la informacion y almacena los datos en firebase 
Inicio de sesión:
El usuario ingresa sus datos, el sistema los verifica y si estan correctas se dirige a la seccion de gestion de su cultivo.

2. Gestión y seguimiento del cultivo:
si es un usuario nuevo debe registrarse y acceder al la seccion de  gestón de cultivos registrar la fecha de siembra y subir imagenes
de la evolucion desde que se hizo la siembra y el sistema alamcenara sus datos y procedera a monitorearlo.
Una vez que el usuario iniciada la seccion el sistema procedra a llevarlo a la sseccion donde le esta monitoreando el cultivo.

3. Reporte de problemas:
El usuario detecta un problema en su cultivo, accede al sistema a la seccion de reportes sube la imagen detallada del daño y la descripción.
la informacion se alamacenar aen firebase.

4.Notificaciones y alertas:
El sistema calcula la fecha de fertilizacion segun la fecha de siembra; Firebase Cloud Messaginenviara una notificacion para recordarle la fertilización.

5. Interfaz de ususario:
El sistema cuenta con una interfaz accesible para los agricultores, con un diseño iteractivo  y de colores naturales 
 Pantalla de Inicio:con botones que permite el registro e inicio de sesión con Firebase , validando datos y permitiendo la recuperación de contraseña.
una vez ingresado al sistema  Presenta un resumen de los cultivos registrados con datos clave como fecha de siembra, tipo de papa y estado del cultivo.
Incluye un botón para agregar ,nuevos cultivos y una sección de notificaciones, Gestión de Cultivos: Permite registrar nuevos cultivos ingresando fecha
 de siembra,además de subir una imagen desde cero, los datos se almacenan en Firebase Firestore.
Monitoreo del Cultivo: Muestra una línea de tiempo con imágenes y notas sobre la evolución del cultivo. Se pueden subir nuevas fotos y registrar observaciones.
Reporte de Problemas: Permite a los agricultores reportar plagas o enfermedades mediante imágenes y descripciones detalladas, almacenando los reportes y generando
 alertas para fertilizacion oportuna.
 Notificaciones: Muestra alertas automáticas sobre fertilización y problemas enviadas mediante Firebase Cloud Messaging.
Configuración: Permite modificar datos del usuario, configurar notificaciones, cambiar la contraseña y cerrar sesión. 


Tecnologias
-
El proyecto se desarrollara en el lenguaje de programación javascrip en el ID VS code  se implementara  HTML y CSS para diseñar
la estructura y estilo de la interfaz grafica del sistema para que atractiva y accesible de el sistema  , Node.js y Express.js 
para gestionar los datos .Firebase storage la elegi para almacenar las imagenes en el sistema Firebase NoSQL es la base de datos para almacenar la informacion.
Firebase cloud Messagin es para enviar las notificaciones y alertas a los usuarios.


integrantes:
-
[Mayra Karina Sanchez Sanchez](https://github.com/Karina-1411Sanchez)
