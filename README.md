
---

# **MERN Mahanaym Management System**

Este es un sistema de gestión escolar completo construido con el stack **MERN** (MongoDB, Express.js, React.js, Node.js). El proyecto incluye un backend robusto y un frontend moderno con características como autenticación, gestión de usuarios, clases, estudiantes, profesores y más.

---

## **Tabla de Contenidos**

1. [Requisitos Previos](#requisitos-previos)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Configuración del Backend](#configuración-del-backend)
4. [Configuración del Frontend](#configuración-del-frontend)
5. [Ejecución del Proyecto](#ejecución-del-proyecto)
6. [Variables de Entorno](#variables-de-entorno)
7. [Contribuciones](#contribuciones)
8. [Licencia](#licencia)

---

## **Requisitos Previos**

Antes de ejecutar el proyecto, asegúrate de tener instalado lo siguiente:

- **Node.js**: Versión 18 o superior ([Descargar Node.js](https://nodejs.org/))
- **npm** o **Yarn**: Gestor de paquetes para JavaScript.
- **MongoDB**: Base de datos NoSQL. Puedes usar una instancia local o MongoDB Atlas ([MongoDB Atlas](https://www.mongodb.com/cloud/atlas)).
- **Git**: Para clonar el repositorio ([Descargar Git](https://git-scm.com/)).

---

## **Estructura del Proyecto**

El proyecto está dividido en dos carpetas principales:

```
/MERN-Mahanaym-Management-System
  ├── /backend          # Código del servidor (Node.js + Express.js)
  └── /frontend         # Interfaz de usuario (React.js)
```

---

## **Configuración del Backend**

### **1. Clonar el Repositorio**
```bash
git clone https://github.com/tu-usuario/MERN-Mahanaym-Management-System.git
cd MERN-Mahanaym-Management-System/backend
```

### **2. Instalar Dependencias**
```bash
cd backend
npm install
```

### **3. Configurar Variables de Entorno**
Crea un archivo `.env` en la carpeta `/backend` con las siguientes variables:

```env
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>?retryWrites=true&w=majority
JWT_SECRET=your_jwt_secret_key
```

> **Nota**: Reemplaza `<username>`, `<password>` y `<dbname>` con tus credenciales de MongoDB.

### **4. Ejecutar el Servidor**
```bash
npm run dev
```

El servidor se ejecutará en `http://localhost:5000`.

---

## **Configuración del Frontend**

### **1. Navegar al Directorio del Frontend**
```bash
cd ../frontend
```

### **2. Instalar Dependencias**
```bash
npm install
```

### **3. Configurar Variables de Entorno**
Crea un archivo `.env` en la carpeta `/frontend` con la siguiente variable:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

> **Nota**: Asegúrate de que esta URL coincida con la dirección de tu backend.

### **4. Ejecutar la Aplicación**
```bash
npm start
```

La aplicación se abrirá automáticamente en `http://localhost:3000`.

---

## **Ejecución del Proyecto**

1. Inicia el servidor backend:
   ```bash
   cd backend
   npm run dev
   ```

2. En otra terminal, inicia el frontend:
   ```bash
   cd frontend
   npm start
   ```

3. Abre tu navegador y navega a `http://localhost:3000`.

---

## **Variables de Entorno**

### **Backend**
- `PORT`: Puerto en el que se ejecutará el servidor.
- `MONGO_URI`: URI de conexión a MongoDB.
- `JWT_SECRET`: Secreto para firmar tokens JWT.

### **Frontend**
- `REACT_APP_API_URL`: URL base del backend.

---

## **Contribuciones**

Si deseas contribuir al proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m "Añadir nueva funcionalidad"`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

---

## **Licencia**

Este proyecto está bajo la licencia **GNU**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## **Contacto**

Si tienes preguntas o sugerencias, no dudes en contactarme:

- **Nombre**: Yeshua Amador Chiliquinga Amaya
- **Correo Electrónico**: yachiliquinga1@espe.edu.ec
- **GitHub**: [tu-usuario](https://github.com/YeshuaChiliquingaAmaya)

---

¡Gracias por descargar y usar este proyecto! Esperamos que sea útil para ti y tu equipo. 🚀
