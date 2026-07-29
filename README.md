Laboratorio de Autenticación con Firebase
Descripción

Este proyecto fue desarrollado como parte de un laboratorio para aprender a utilizar Firebase Authentication en una aplicación web.

El objetivo del laboratorio fue crear un sistema básico de autenticación donde un usuario pueda registrarse, iniciar sesión, acceder a una página protegida y cerrar sesión utilizando Firebase.

Funcionalidades
Registro de usuarios con correo electrónico y contraseña.
Inicio de sesión.
Protección de la página principal para usuarios autenticados.
Cierre de sesión.
Validación del estado de autenticación.
Tecnologías utilizadas
HTML5
CSS3
JavaScript (ES6 Modules)
Firebase Authentication
Estructura del proyecto
firebase-auth-lab/
│
├── index.html
├── registro.html
├── dashboard.html
│
├── css/
│   └── styles.css
│
├── js/
│   └── app.js
│
└── README.md
Configuración

Para ejecutar este proyecto es necesario crear un proyecto en Firebase y habilitar el método de autenticación por Correo electrónico y contraseña.

Después, se debe reemplazar la configuración de Firebase en el archivo app.js por la configuración del proyecto correspondiente.

Cómo ejecutar el proyecto
Clonar el repositorio.
git clone https://github.com/trabajodavidg/firebase-auth-lab.git
Entrar a la carpeta del proyecto.
cd firebase-auth-lab
Abrir el proyecto con Visual Studio Code.
Ejecutar un servidor local (por ejemplo, usando la extensión Live Server).
Abrir el navegador y probar el registro, el inicio de sesión y el cierre de sesión.
Aprendizajes

Con este laboratorio aprendí a:

Crear un proyecto en Firebase.
Configurar Firebase Authentication.
Registrar usuarios desde una aplicación web.
Iniciar sesión utilizando Firebase.
Proteger una página para que solo puedan acceder usuarios autenticados.
Cerrar la sesión del usuario.
Autor

David Guzman

GitHub: https://github.com/trabajodavidg