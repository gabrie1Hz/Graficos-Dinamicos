🥭 Mango Dashboard | Panel de Administración Dinámico 🧡💛

¡Bienvenido al Dashboard de Mangos! Un sistema completo de administración con visualización de datos, gráficos interactivos, registros y login seguro. Pensado especialmente para la gestión de productos, ventas y clientes en un entorno moderno y colorido 🌈.
🚀 Características Principales

✅ Login y Registro Seguro con validación y almacenamiento de contraseñas hasheadas.
✅ Panel de Administración Dinámico con gráficos actualizados en tiempo real.
✅ Gráficas interactivas (Barras, Pastel) con datos desde la base de datos y archivos externos.
✅ Carga de archivos (.csv, .xlsx, .json) para visualización directa.
✅ Modo claro y oscuro 🌙☀️ configurable por el usuario.
✅ Generación de Reportes en PDF 📊📝 para descarga automática.
✅ Responsive Design 📱💻 (Adaptado a móviles y escritorio).


🗂️ Arquitectura del Proyecto (MVC/Capas)

📦 XFORCE-Dashboard
 ┣ 📂 backend      # Lógica de negocio (PHP + MySQL + Controladores)
 ┃ ┣ 📜 BD.php     # Conexión a la base de datos
 ┃ ┣ 📜 getData.php # Endpoints para Dashboard
 ┃ ┣ 📜 login.php  # Lógica de inicio de sesión
 ┃ ┗ 📜 registro.php # Registro de usuarios
 ┣ 📂 public       # Vista (HTML + CSS + JS)
 ┃ ┣ 📂 css
 ┃ ┃ ┗ 📜 styles.css  # Estilos modernos (tema mango)
 ┃ ┣ 📂 js
 ┃ ┃ ┗ 📜 script.js  # Lógica de frontend y conexión con gráficos
 ┃ ┣ 📜 graficos.php # Panel principal con estadísticas
 ┃ ┣ 📜 iniciarsesion.html # Interfaz login
 ┃ ┗ 📜 registro.html # Interfaz registro
 ┗ 📜 README.md


🎨 Vista del Login (Inspirado en Mangos 🥭)

💻 Login de Acceso Moderno       📝 Registro de Nuevos Usuarios

📊 Ejemplo de Dashboard Dinámico

📈 Gráficos Dinámicos            🛒 Panel de Productos, Clientes y Ventas



💾 Base de Datos MySQL

Tablas integradas:

    usuarios (para login y registro) 🔐
    productos (gestión de inventario) 📦
    ventas (registro de ventas) 💰
    cliente (clientes asociados) 👥
    desglose (detalles de ventas) 🧾

🎯 Nota: Script completo de la base de datos en carpeta /sql (próximamente).


⚙️ Tecnologías Utilizadas

    PHP 8+ 🐘
    MySQL / MariaDB 🗄️
    HTML5, CSS3, JavaScript (Vanilla) 🌐
    Chart.js 📊 (Gráficas dinámicas)
    jsPDF + html2canvas 📝 (Reportes PDF)
    PapaParse / SheetJS 📥 (Lectura de archivos CSV/Excel)


    📥 Instalación Rápida

    🚀 Clona este repositorio:

     git clone https://github.com/tuusuario/mango-dashboard.git


     🔧 Configura la base de datos (crear DB dashboard y tablas).

⚙️ Ajusta tu conexión a la base de datos en:


/backend/BD.php


🖥️ Corre tu servidor local (XAMPP, Laragon, MAMP).

🎉 Accede al login:

http://localhost/XFORCE/dashboard/public/iniciarsesion.html


💡 Prueba de Acceso

    Usuario de ejemplo para login:


    Usuario: admin
Contraseña: admin123
⚠️ Cambia o registra nuevos usuarios desde la interfaz de registro.

🧑‍💻 Contribución

¡Las contribuciones son bienvenidas!
Si deseas proponer cambios o mejorar el panel:

    Fork 🍴 este repositorio.
    Crea una branch con tu mejora: feature/nueva-funcionalidad.
    Haz un commit y un pull request ✅.


    📬 Contacto

💌 Si te gustó este proyecto, ¡no olvides dar ⭐ y compartirlo!
Contacto: s4vitar11@gmail.com

⚠️ Nota

    Este proyecto es académico/demostrativo. No usar en producción sin ajustes de seguridad adicionales (CSRF, validaciones avanzadas, etc.).

🌟 Créditos

Desarrollado por [p1r4t3h00k] 🥭🧡
Canal de youtube en donde doy clases de ciberseguridad y hacking etico: https://www.youtube.com/@P1r4t3h00k/
