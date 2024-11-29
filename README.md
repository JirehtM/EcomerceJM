TERMINAL BACKEND:

1. npm init -y
Qué hace: Crea un archivo package.json con la configuración básica de tu proyecto.
Detalle: La opción -y rellena automáticamente las preguntas con valores predeterminados (nombre del proyecto, versión, etc.), evitando que tengas que responderlas manualmente.
2. npm install express nodemon
Qué hace: Instala dos paquetes de Node.js:
express: Un framework para construir aplicaciones web y APIs de forma rápida y sencilla.
nodemon: Una herramienta que reinicia automáticamente tu servidor cuando detecta cambios en tu código.
Resultado: Los paquetes quedan registrados en package.json (en dependencies para express y en devDependencies para nodemon, si usaste la bandera --save-dev).
3. npm install mongoose
Qué hace: Instala Mongoose, una librería de Node.js para trabajar con bases de datos MongoDB. Simplifica las consultas y la gestión de datos mediante esquemas y modelos.


TERMINAL FRONTEND:


1. npx create-react-app frontend
Qué hace: Crea un nuevo proyecto de React llamado frontend.
Detalle:
npx: Ejecuta paquetes de npm sin instalarlos globalmente.
create-react-app: Una herramienta para configurar rápidamente un proyecto de React con una estructura predeterminada y las configuraciones necesarias.
Resultado: Una carpeta frontend con todo listo para empezar a desarrollar una aplicación React.
2. npm install axios react-router-dom @material-tailwind/react
Qué hace: Instala tres paquetes útiles para el desarrollo en React:
axios: Librería para hacer solicitudes HTTP fácilmente.
react-router-dom: Herramienta para gestionar rutas y navegación dentro de la aplicación React.
@material-tailwind/react: Componentes preconstruidos y estilizados con Tailwind CSS para mejorar el diseño de tu interfaz.
Resultado: Los paquetes quedan registrados en el archivo package.json y están listos para usarse en tu proyecto.
