<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/919/919830.png" />

# 🚀 Laravel Rental Management System

### Plataforma web moderna desarrollada con Laravel ⚡

<p align="center">
  <b>Laravel Rental Management System</b> es una plataforma full stack diseñada para la administración de rentas, reservas y gestión de usuarios utilizando el poderoso framework Laravel.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-FullStack-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
  <img src="https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-WebApp-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-estructura-del-proyecto">Estructura</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Laravel Rental Management System** es una aplicación web construida con Laravel orientada a la administración de propiedades, eventos, vehículos o servicios de renta mediante un sistema moderno, seguro y escalable.

La plataforma permite:

- 🏠 Gestionar propiedades o productos en renta
- 👥 Administrar usuarios y clientes
- 📅 Gestionar reservas
- 💳 Controlar pagos
- 📊 Visualizar estadísticas administrativas
- 🔐 Gestionar autenticación y permisos
- ⚡ Automatizar operaciones del sistema

---

# ✨ Características

## 🏠 Gestión de rentas

- 📋 Registro de propiedades o artículos
- 📅 Gestión de reservas
- 💰 Administración de precios
- 📍 Gestión de ubicaciones
- 🖼️ Carga de imágenes
- ⚡ Disponibilidad en tiempo real

---

## 👥 Gestión de usuarios

- 👤 Registro e inicio de sesión
- 🔐 Autenticación segura
- 📄 Gestión de perfiles
- 🛡️ Roles y permisos
- 📊 Administración centralizada

---

## 📊 Panel administrativo

- 📈 Dashboard interactivo
- 📅 Control de reservas
- 👥 Administración de usuarios
- 💰 Reportes financieros
- ⚡ Gestión completa del sistema

---

## 🔔 Automatización

- 📧 Notificaciones automáticas
- 🔄 Migraciones de base de datos
- ⚙️ Sistema modular
- 🚀 Arquitectura escalable

---

# 👨‍💼 Módulos del sistema

## 🏠 Rental Module

Módulo principal encargado de la gestión de artículos o propiedades en renta.

### Funcionalidades:

- ➕ Crear registros
- 🖼️ Subir imágenes
- 💰 Configurar precios
- 📅 Gestionar disponibilidad
- 📋 Información detallada

---

## 👤 User Module

Módulo dedicado a usuarios y autenticación.

### Funcionalidades:

- 🔐 Login y registro
- 👥 Gestión de usuarios
- 📄 Administración de perfiles
- 🛡️ Roles y permisos

---

## 📊 Admin Module

Panel administrativo del sistema.

### Funcionalidades:

- 📈 Dashboard
- 📅 Gestión de reservas
- 👥 Control de usuarios
- ⚙️ Configuración del sistema
- 📊 Estadísticas administrativas

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel" />
</p>

- PHP 8+
- Laravel
- Eloquent ORM
- Sistema MVC
- Middleware
- API REST

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Migraciones
- Relaciones SQL
- Persistencia de datos

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman" />
</p>

- Git
- GitHub
- Visual Studio Code
- Composer
- Postman

---

# 📂 Estructura del proyecto

```bash
Laravel-Rental-Management-System/
│
├── app/                      # Lógica principal
├── bootstrap/                # Bootstrap Laravel
├── config/                   # Configuración
├── database/                 # Migraciones y seeders
├── public/                   # Archivos públicos
├── resources/                # Vistas y assets
├── routes/                   # Rutas web y API
├── storage/                  # Archivos del sistema
├── tests/                    # Testing
├── artisan                   # CLI Laravel
├── composer.json
├── package.json
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 8+
- Composer
- MySQL
- Node.js
- Laravel
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/Laravel-Rental-Management-System.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd Laravel-Rental-Management-System
```

---

## 3️⃣ Instalar dependencias PHP

```bash
composer install
```

---

## 4️⃣ Instalar dependencias frontend

```bash
npm install
```

---

## 5️⃣ Configurar variables de entorno

```bash
cp .env.example .env
```

---

## 6️⃣ Generar clave Laravel

```bash
php artisan key:generate
```

---

## 7️⃣ Configurar base de datos

Editar:

```bash
.env
```

Agregar:

```env
DB_DATABASE=laravel_rental
DB_USERNAME=root
DB_PASSWORD=
```

---

## 8️⃣ Ejecutar migraciones

```bash
php artisan migrate
```

---

## 9️⃣ Ejecutar servidor

```bash
php artisan serve
```

---

## 🔟 Ejecutar Vite

```bash
npm run dev
```

---

# 📊 Funcionalidades principales

## 🏠 Gestión de rentas

- Registro de propiedades
- Gestión de reservas
- Disponibilidad en tiempo real
- Administración de precios

---

## 👥 Administración de usuarios

- Roles administrativos
- Gestión de clientes
- Seguridad y autenticación
- Control de accesos

---

## 📈 Dashboard

- Estadísticas del sistema
- Reportes administrativos
- Gestión centralizada
- Control de operaciones

---


# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo full stack
- Arquitectura MVC
- Gestión de bases de datos
- CRUD avanzados
- Sistemas administrativos
- Laravel Framework
- APIs modernas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Deploy cloud
- 💳 Pasarela de pagos
- 🤖 Recomendaciones inteligentes
- 📊 Analytics avanzados
- 🌐 API pública
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas web modernas, Laravel y sistemas administrativos 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y desarrollo de plataformas modernas con Laravel.

---

<div align="center">

### 🚀 Laravel Rental Management System — administración inteligente y moderna ⚡

</div>
