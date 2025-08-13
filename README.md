# 📄 Proyecto-integrador-tecmilenio

## 📌 Descripción
Aplicación web desarrollada en **Java (Servlets y JSP)** como parte de la Actividad 3 del certificado de programación, que calcula el área de un triángulo y utiliza **sesiones** y **cookies** para almacenar el nombre del usuario y el último cálculo realizado.

---

## 🚩 Problema Identificado
En muchas aplicaciones web, los datos ingresados por el usuario no se guardan entre sesiones, lo que obliga a reingresarlos en cada visita y disminuye la experiencia de uso.

---

## 💡 Solución
Este proyecto implementa:
- Uso de **atributos de sesión** para almacenar el nombre del usuario.
- **Cookies** para guardar el último cálculo de área realizado.
- Página principal (`index.jsp`) que saluda al usuario y muestra el último cálculo si está disponible.
- Servlet encargado de procesar datos y delegar el cálculo a la clase `Triangulo`.

---

## 🏗 Arquitectura
**Componentes principales:**
- **Frontend:** JSP con HTML5, CSS y Bootstrap.
- **Backend:** Servlets en Java.
- **Servidor Web:** Apache Tomcat 10.
- **Persistencia temporal:** Sesiones y cookies.
- **Lógica de negocio:** Clase `Triangulo`.

![Diagrama de Arquitectura](docs/arquitectura.png)

---

## 📚 Tabla de Contenidos
- [Descripción](#-descripción)
- [Problema Identificado](#-problema-identificado)
- [Solución](#-solución)
- [Arquitectura](#-arquitectura)
- [Requerimientos](#-requerimientos)
- [Instalación](#-instalación)
- [Roadmap](#-roadmap)
## Roadmap

A continuación se presentan las mejoras y funciones planificadas para versiones futuras:

- Implementar autenticación con OAuth 2.0 (Google y Facebook).
- Agregar soporte para múltiples idiomas.
- Mejorar el diseño responsivo para dispositivos móviles.
- Incluir reportes descargables en PDF y Excel.
- Integrar notificaciones por correo electrónico para eventos importantes.
- Optimizar consultas a la base de datos para mejorar el rendimiento.## Instalación

1. Clonar el repositorio desde GitHub:
   ```bash
   git clone https://github.com/usuario/nombre-repo.git- [Configuración](#-configuración)
## Configuración

1. Abrir el archivo `config.properties` ubicado en la carpeta `src/main/resources`.
2. Configurar la conexión a la base de datos:

- [Uso](#-uso)
## Uso

### Usuario Final
1. Abrir el navegador y acceder a `http://localhost:8080/miapp`.
2. Iniciar sesión con las credenciales registradas.
3. Navegar por el menú principal para acceder a las funciones disponibles.
4. Cerrar sesión al terminar.

### Administrador
1. Iniciar sesión con usuario administrador.
2. Acceder al panel de administración.
3. Gestionar usuarios, permisos y configuración del sistema.
4. Revisar los reportes y estadísticas.
- [Contribución](#-contribución)
## Contribución

1. Realiza un fork del repositorio.
2. Crea una rama para tu nueva funcionalidad:
   ```bash
   git checkout -b mi-nueva-funcionalidad- [Roadmap](#-roadmap)
- [Producto](#-producto)

---

## 📋 Requerimientos

### Servidores
- Apache Tomcat 10.1.x

### Paquetes adicionales
- JSTL 1.2
- Bootstrap 5.x

### Versión de Java
- Java SE 17

---

## ⚙ Instalación

### 1️⃣ Instalar el ambiente de desarrollo
```bash
# Clonar repositorio
git clone https://github.com/TU-USUARIO/Proyecto-integrador-tecmilenio.git
cd Proyecto-integrador-tecmilenio

# Importar en Visual Studio Code o NetBeans Proyecto-integrador-tecmilenio
Proyecto integrador breve para certificado de programación
