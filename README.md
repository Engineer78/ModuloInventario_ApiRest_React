# **Hardware Store Inventory - FFIG (Frontend + Backend)**

Este proyecto unifica los desarrollos previos de frontend y backend en una sola aplicación integrada, como parte de la Evidencia: GA7-220501096-AA5-EV04. Se presenta una solución completa que incluye una aplicación web con React + Vite y una API REST desarrollada en Java utilizando Spring Boot con JPA, conectada a una base de datos MySQL.

# 📋 **Descripción:**

La aplicación permite gestionar integralmente el inventario de una ferretería mediante operaciones CRUD (Crear, Leer, Actualizar, Eliminar) para productos, proveedores y categorías. El frontend interactúa directamente con el backend usando Axios y hooks de React como useEffect, facilitando una experiencia dinámica y eficiente.

# 🚀 **Tecnologías Utilizadas:**

Frontend

JavaScript

React + Vite

Axios

HTML5 & CSS3

Backend

Java

Spring Boot

Spring Data JPA

Maven

MySQL (phpMyAdmin)

# ⚙️ **Instalación y Uso:**

# **Base de Datos**

Crea la estructura básica de la base de datos MySQL usando phpMyAdmin.

Modifica el archivo application.properties ubicado en:

backend/src/main/resources/application.properties

Asegúrate de configurar correctamente los siguientes parámetros según tu entorno:

spring.datasource.url=jdbc:mysql://localhost:3306/nombre_tu_base_datos
spring.datasource.username=TU_USUARIO
spring.datasource.password=TU_CONTRASEÑA

# **Backend (API REST)**

Clona el repositorio y ejecuta la API:

git clone --recurse-submodules https://github.com/Engineer78/ModuloInventario_ApiRest_React.git
cd Backend/Inventario-HardwareStoreInventory
mvn spring-boot:run

La API estará disponible en: http://localhost:8080.

# **Frontend (React)**

Instala las dependencias y ejecuta el frontend:

npm install
npm run dev

Accede a la aplicación web desde: http://localhost:5173.

# **Inicio de sesión:**

Utiliza las siguientes credenciales para probar la aplicación:

Usuario: admin@gmail.com

Contraseña: 12345

👥 **Contribuidores**

Proyecto desarrollado por aprendices del SENA Centro de Comercio y Turismo de Armenia, Regional Quindío:

Juan David Gallego López (Ficha: 2879723)

Joaquín H. Jiménez Rosas (Ficha: 2879723)

David Ricardo Graffe Rodríguez (Ficha: 2979724)

🎓 **Instructora**

Ing. Diana María Valencia Rebellón (SENA - Regional Quindío)

📝 **Licencia:**

Este proyecto es formativo y no posee una licencia de distribución. Su uso es exclusivo para fines educativos dentro del SENA.

**CopyRight © 2024-2025 @JuDaJoSystemSoft. All rights reserved.**
