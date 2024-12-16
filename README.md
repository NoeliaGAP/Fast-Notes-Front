<img src="src/assets/imgs/Fasty Notes.png" alt="Cover Fasty Notes"/>

<div style="display: flex; align-items: center;">
  <p style="margin-right: 10px;">
    Este proyecto es una aplicación de notas que permite a los usuarios crear, editar, eliminar y gestionar notas con funcionalidades adicionales como la subida de imágenes, autenticación segura mediante JWT, y un diseño atractivo utilizando Tailwind CSS.
  </p>
  <img src="src/assets/imgs/post-it2.gif" alt="PostIt Gif" width="205"/>
</div>


## Tecnologías utilizadas

- **Frontend**:

<div>
<img src="src/assets/imgs/reactjs.png" alt="React.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/typescript.png" alt="Typescript Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/tailwind.png" alt="Tailwind Icon" width="60" style="margin: 0 7.5px"/>
</div>

- **Backend**:  

<div>
<img src="src/assets/imgs/nodejs.png" alt="Node.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/express-js.svg" alt="Express.JS Icon" width="60" style="margin: 0 7.5px"/>
  &nbsp;
<img src="src/assets/imgs/mongodb.svg" alt="MongoDB Icon" width="60" style="margin: 0 7.5px"/>
</div>

- **Seguridad**:  
  - JSON Web Tokens (JWT)

- **Otras características**:  
  - Gestión y subida de imágenes.

## Lo que aprendí en este proyecto

1. **Integración de tecnologías frontend y backend**:
   - Creación de una API RESTful eficiente y segura.
   - Conexión entre frontend y backend con Axios.

2. **Autenticación y seguridad**:
   - Implementación de JWT para proteger las rutas del backend y gestionar sesiones de usuario.

3. **Gestión de datos**:
   - Uso de MongoDB como base de datos no relacional para almacenar información estructurada.

4. **Estilo y diseño responsivo**:
   - Utilización de Tailwind CSS para construir una interfaz de usuario moderna, limpia y totalmente responsiva.

5. **Subida y manejo de archivos**:
   - Implementación de funcionalidades para la subida de imágenes y su correcta gestión en el backend.

6. **Flujo de desarrollo**:
   - Configuración y gestión de un entorno de desarrollo eficiente para frontend y backend por separado.

## Requisitos previos

- Node.js instalado (v16 o superior recomendado).  
- MongoDB configurado y corriendo en tu máquina o acceso a un clúster remoto.  
- Git instalado (opcional, para clonar el repositorio).  

## Cómo ejecutar el proyecto

1. **Clonar el repositorio**  
   ```
   git clone https://github.com/NoeliaGAP/Fast-Notes-Front
   ```
   - Abre la carpeta **notes-back** e instala las dependencias con:
     ```
     npm i
     ```
   - Crea un archivo *.env* en **notes-back** y agrega las variables de entorno:
     ```
     VITE_API_URL=http://localhost:3000
     ```
   - Corre el proyecto con:
     ```
     npm run dev
     ```
2. **Configuración del backend**
   - clona el repositotio
     ```
      https://github.com/NoeliaGAP/Fast-Notes-Back
     ```
   - Abre la carpeta notes-back e instala las dependecias:   
     ```
     npm i
     ```

   - Inicia el servidor:
     ```bash
     npm run dev
     ```