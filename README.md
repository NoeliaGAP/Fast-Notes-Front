<img src="src/assets/imgs/Fasty Notes.png" alt="Cover Fasty Notes"/>

<div style="display: flex; align-items: center;">
  <p style="margin-right: 10 px;">
    Este proyecto es una aplicación de notas que permite a los usuarios gestionar sus notas de manera eficiente. Entre sus funcionalidades principales se incluyen la creación, edición, eliminación de notas, subida de imágenes, autenticación segura mediante JWT, y un diseño moderno utilizando Tailwind CSS.
  </p>
  <img src="src/assets/imgs/post-it2.gif" alt="PostIt Gif" width="205"/>
</div>

## Tecnologías Utilizadas

### **Frontend:**

<div>
<img src="src/assets/imgs/reactjs.png" alt="React.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/typescript.png" alt="Typescript Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/tailwind.png" alt="Tailwind Icon" width="60" style="margin: 0 7.5px"/>
</div>

### **Backend:**

<div>
<img src="src/assets/imgs/nodejs.png" alt="Node.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/express-js.svg" alt="Express.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/mongodb.svg" alt="MongoDB Icon" width="60" style="margin: 0 7.5px"/>
</div>

### **Seguridad:**

- JSON Web Tokens (JWT)

### **Otras Características:**

- Gestor de imágenes para la subida y manejo eficiente de archivos.

## Lo que Aprendí

1. **Integración Frontend y Backend:**

   - Diseño e implementación de una API RESTful eficiente y segura.
   - Conexión entre frontend y backend utilizando Axios.

2. **Autenticación y Seguridad:**

   - Uso de JWT para proteger rutas del backend y gestionar sesiones de usuario.

3. **Gestor de Datos:**

   - Implementación de MongoDB como base de datos no relacional para manejar información estructurada.

4. **Estilo y Diseño Responsivo:**

   - Construcción de una interfaz de usuario moderna y adaptativa con Tailwind CSS.

5. **Subida de Archivos:**

   - Desarrollo de funcionalidades para subir y gestionar imágenes desde el frontend al backend.

6. **Flujo de Desarrollo:**

   - Configuración de un entorno de desarrollo eficiente para manejar frontend y backend de manera separada.

## Requisitos Previos

- **Node.js**: Versión 16 o superior recomendada.
- **MongoDB**: Configurado localmente o acceso a un clúster remoto.
- **Git**: Opcional, para clonar el repositorio.

## Cómo Ejecutar el Proyecto

### 1. Clonar los Repositorios

#### Frontend:

```bash
git clone https://github.com/NoeliaGAP/Fast-Notes-Front.git
```

- Accede a la carpeta del proyecto:
  ```bash
  cd notes-front
  ```
- Instala las dependencias:
  ```bash
  npm install
  ```
- Crea un archivo `.env` con la siguiente variable:
  ```env
  VITE_API_URL=http://localhost:3000
  ```
- Inicia el servidor de desarrollo:
  ```bash
  npm run dev
  ```

#### Backend:

```bash
git clone https://github.com/NoeliaGAP/Fast-Notes-Back
```

- Accede a la carpeta del proyecto:
  ```bash
  cd notes-back
  ```
- Instala las dependencias:
  ```bash
  npm install
  ```
- Configura el archivo `.env` con las variables necesarias, por ejemplo:
  ```env
  MONGO_URI=<tu_uri_de_mongodb>
  JWT_SECRET=<tu_secreto_jwt>
  ```
- Inicia el servidor de desarrollo:
  ```bash
  npm run dev
  ```

### 2. Acceder a la Aplicación

- Abre el navegador y accede a `(https://fasty-notes.netlify.app)` para interactuar con la aplicación.

## Funcionalidades Destacadas

- **Gestor de Notas:**
  - Crear, editar y eliminar notas de manera eficiente.
- **Autenticación Segura:**
  - Registro e inicio de sesión protegidos mediante JWT.
- **Subida de Imágenes:**
  - Integración con backend para almacenar y mostrar imágenes.
- **Diseño Responsivo:**
  - Adaptado para funcionar en diferentes dispositivos y resoluciones.

## Contacto

Si tienes alguna duda o sugerencia, no dudes en contactarme a través de [mi LinkedIn](https://www.linkedin.com/in/noelia-gap/) o visita el repositorio para más información.

