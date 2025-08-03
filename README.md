# Mister PC Boteo Sistema de Paneles Gestión  Web

Mister PC Boteo es una plataforma web  en desarrollo diseñada para gestionar eficientemente los servicios de reparación, mantenimiento y venta de productos tecnológicos. El sistema cuenta con tres paneles principales: **Administrador**, **Técnico** y **Usuario/Cliente**.

---

## Estructura del Proyecto

- `panel_admin/`: Panel para el administrador del sistema.
- `panel_tecnico/`: Panel para técnicos registrados.
- `panel_usuario/`: Panel para usuarios o clientes.

---

## Panel de Administrador

El panel de administrador es el núcleo de control de todo el sistema. Las funcionalidades principales incluyen:

- 🔧 **Gestión de Técnicos**:
  - Registrar, editar o eliminar técnicos.
  - Ver estado y actividad de cada técnico.
  
- 📦 **Gestión de Productos**:
  - Agregar productos nuevos con información como: imagen, nombre, precio, categoría, tipo de presentación (unidad o caja), cantidad en stock, etc.
  - Editar o eliminar productos existentes.
  - Añadir nuevas categorias.
  - Visualizar productos por categoría o disponibilidad.
  
- 🛠️ **Gestión de Equipos Asignados**:
  - Asignar dispositivos (laptops, PCs, etc.) a los técnicos para reparación.
  - Ver historial de dispositivos, reparaciones y cambios de estado.
  - Agregar equipo, llevar seguimiento, editar y ver información del equipo asi como poder eliminar equipo.
  - 

- 📊 **Dashboard**:
  - Visualización general del sistema: número de productos, técnicos activos, equipos en reparación, etc.

- 👥 **Gestión de Usuarios**:
  - Ver todos los usuarios registrados.
  

---

## 🧑‍🔧 Panel de Técnico

El técnico inicia sesión en su panel personalizado, donde puede:

- 📋 **Ver Equipos Asignados**:
  - Acceso a la lista de dispositivos que debe revisar o reparar.
  - Ver detalles del equipo, asi como poder añadir un nuevo equipo y actualizar información.

- ✏️ **Actualizar Estado del Equipo**:
  - Cambiar el estado (en reparación, reparado, entregado, etc.).
  - Subir observaciones o adjuntar evidencia de reparación.

- 👤 **Editar Perfil**:
  - Cambiar su nombre, especialidad, correo electrónico o contraseña.

---

## 👤 Panel de Usuario/Cliente

Los usuarios pueden acceder a su panel privado donde tienen disponible:

- 💻 **Seguimiento de Equipos**:
  - Revisar el estado actual de sus dispositivos en reparación.
  - Ver información, nombre del técnico asignado y observaciones.
  - Historial de equipos que han sido reparados en la empresa.


---

## 🔒 Seguridad y Roles

El sistema gestiona tres tipos de roles con permisos específicos:

| Rol         | Acceso a                           | Restricciones                        |
|-------------|------------------------------------|--------------------------------------|
| Admin       | Todo el sistema                    | Ninguna                              |
| Técnico     | Solo equipos asignados y su perfil | No puede acceder a otros módulos     |
| Usuario     | Solo sus equipos y perfil          | No puede ver productos internos ni técnicos |

---

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, Bootstrap, CSS3, JavaScript básico
- **Backend**: PHP (por agregar)
- **Base de Datos**: MySQL (por agregar)
- **Hosting**: XAMPP o servidor compatible (en proceso)

---

## 📌 Estado del Proyecto

En desarrollo. Se están incorporando mejoras como:

- Soporte para productos por unidad y por caja.
-Implementación de funcionalidad backend con  MySQL.
- Mejora de la interfaz móvil.

---

## ✨ Autor

Desarrollado por Daniel Alas – Estudiante de Ingeniería en Sistemas y Computación.

