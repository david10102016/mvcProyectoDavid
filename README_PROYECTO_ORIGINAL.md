# 🛒 Proyecto MVC - Sistema de Gestión de Inventario

Este es un proyecto web desarrollado con **ASP.NET Core MVC (.NET 8.0.4)** para la gestión de productos e inventario, basado en capas y siguiendo buenas prácticas de arquitectura MVC.

---

## 🔧 Tecnologías Utilizadas

- ASP.NET Core MVC 8.0.4
- Entity Framework Core
- SQL Server
- Bootstrap 5.3
- Visual Studio 2022

---

## 📁 Estructura del Proyecto

- `Models/` → Clases de entidad como Producto, Almacén, Categoría
- `Controllers/` → Controladores organizados por módulo
- `Views/` → Vistas divididas por módulos con operaciones CRUD
- `Data/AppDbContext.cs` → Contexto de base de datos con EF Core
- `appsettings.json` → Cadena de conexión configurada para SQL Server

---

## 🧩 Módulos Incluidos

- **Productos**: Gestión de productos (crear, editar, eliminar, listar)
- **Almacenes**: Gestión de ubicaciones de productos
- **Categorías**: Organización de productos por tipo
- **Usuarios (Identity)**: Manejo de roles y usuarios con autenticación

---

## ⚙️ Instalación y Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/ProyectoMVC_Inventario.git
   ```

2. Abre el proyecto en **Visual Studio 2022**

3. Restaura los paquetes NuGet:
   - `Build > Restore NuGet Packages`

4. Configura la conexión en `appsettings.json` apuntando a tu instancia de SQL Server.

5. Ejecuta el proyecto (`Ctrl + F5`)

---

## 📸 Captura

![Ejemplo Visual](https://cdn-icons-png.flaticon.com/512/1170/1170627.png)

---

## 🧠 Autor

Desarrollado por Juan david Uscamayta Ramos.  
Proyecto base descargado de GitHub y adaptado para prácticas educativas.

---

## 🪪 Licencia

Distribuido bajo licencia MIT.
