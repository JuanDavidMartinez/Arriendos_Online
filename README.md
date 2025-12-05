# Arriendo Online

Aplicación web construida con **React** para el Frontend y una **API Backend** que permite la administración de inmuebles para arriendo, ofreciendo dos tipos de perfiles: **Arrendador** y **Arrendatario**.

---

## 🚀 Características principales

### 👤 Tipos de usuarios

* **Arrendador**: Puede publicar inmuebles para ofrecer en arriendo.
* **Arrendatario**: Puede buscar inmuebles, filtrar resultados y solicitar más información o agendar citas.

### 🏠 Funcionalidades

#### Para Arrendadores

* Crear, editar y eliminar publicaciones de inmuebles.
* Administrar información detallada (precio, ubicación, imágenes, características, disponibilidad).
* Gestionar solicitudes recibidas y citas programadas.

#### Para Arrendatarios

* Ver listado completo de inmuebles.
* Utilizar filtros avanzados: precio, departamento, ciudad, tipo de inmueble, etc.
* Ver detalles completos de cada inmueble.
* Agendar visitas con el arrendador.
* Enviar mensajes o solicitudes adicionales de información.

---

## 📁 Estructura del proyecto

```
root/
├── Front/           # Aplicación React
│   ├── src/
│   ├── public/
│   └── package.json
└── Backend/         # API REST
    ├── src/
    ├── database/
    └── package.json
```

---

## 🧩 Tecnologías utilizadas

### Frontend (React)

* React + Vite
* React Router
* TailwindCSS
* Axios

### Backend (API)

* Node.js + Express
* Base de Datos (indicar base de datos)
* JWT para autenticación
* Multer para carga de imágenes

---

## ⚙️ Instalación y ejecución

### 1️⃣ Clonar proyecto

```
git clone https://github.com/JuanDavidMartinez/Arriendos_Online.git
cd Arriendos_Online
```

### 2️⃣ Instalar dependencias

#### Frontend

```
cd Front
npm install
```

#### Backend

```
cd Backend
npm install
```

### 3️⃣ Configurar variables de entorno

Crear archivo `.env` en **Backend** con datos como:

```
TODO:
```

---

## ▶️ Ejecución del proyecto

### Frontend

```
npm run dev
```

### Backend

```
npm start
```

---

## 🧪 Endpoints principales del Backend

| Método | Endpoint       | Descripción                    |
| ------ | -------------- | ------------------------------ |
| GET    | /inmuebles     | Lista todos los inmuebles      |
|

---

## 🛡️ Autenticación y Roles

El sistema utiliza JWT para manejar sesiones y roles. Cada usuario tiene un tipo asignado:

* **arrendador**
* **arrendatario**

La API protege rutas específicas dependiendo del rol.

---

## 📌 Roadmap / Mejoras futuras

* Notificaciones en tiempo real.
* Historial de inmuebles arrendados.
* Sistema de calificaciones entre usuarios.
* Integración con pasarelas de pago.
* Chat en tiempo real.

---

## 📄 Licencia

Proyecto de uso libre para fines educativos o comerciales.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Haz un fork del proyecto, crea una rama y envía un pull request.

---

## 📞 Contacto

Si tienes dudas o sugerencias, puedes contactar al desarrollador.
