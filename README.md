# README – Proyecto Node.js + Express + Frontend
## Descripción del Proyecto
Este proyecto combina una API desarrollada en Node.js con Express junto con un frontend ubicado en
la carpeta public/.
Incluye manejo de modelos, controladores, rutas, middlewares y una organización modular orientada a
escalabilidad.
## Estructura del Proyecto
/controllers → Lógica de cada endpoint
/db → Configuración de base de datos
/img → Recursos multimedia
/middleware → Validaciones, autenticación, manejo de errores
/models → Modelos de datos
/node_modules → Dependencias
/public → Archivos visibles desde el navegador (HTML, CSS, JS)
/routes → Rutas de la API
/server → Configuraciones del servidor
.env → Variables de entorno
app.js → Archivo principal del backend
index.js → Script principal del frontend o servidor estático
package.json → Configuración del proyecto
styles.css → Estilos front-end
## Instalación
npm install
## Ejecución del Proyecto
npm start
npm run dev
## Uso del Proyecto
http://localhost:3000
http://localhost:3000/public
## Modelos
Los modelos representan las estructuras de datos del proyecto.
## Rutas
Organizadas por módulos y enlazadas a controladores.
## Variables de Entorno
PORT=3000
DB_HOST=...
DB_USER=...
DB_PASS=...
## Dependencias Principales
express
dotenv
cors
nodemon
body-parser
## Licencia
Proyecto libre para desarrollo y aprendizaje.
