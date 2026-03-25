# Requisitos

## Sprint 1 - Autenticación (Auth)

### Descripción
Este sprint consiste en el desarrollo de las funcionalidades básicas de autenticación y gestión de usuarios dentro del sistema FitData.

El sistema contará con dos roles principales:
- Administrador
- Usuario

---

### Requisitos Generales (Ambos roles)

- El sistema permitirá al usuario iniciar sesión.
- El sistema permitirá al usuario cerrar sesión.
- El sistema permitirá al usuario actualizar su contraseña.
- El sistema permitirá al usuario actualizar o eliminar su imagen de perfil.

---

### Requisitos del Usuario

- El sistema permitirá al usuario visualizar sus datos personales.
- El sistema permitirá al usuario actualizar sus datos personales.

---

### Requisitos del Administrador

#### Gestión de Usuarios
- El sistema permitirá al administrador registrar nuevos usuarios.
- El sistema permitirá al administrador listar los usuarios del sistema.
- El sistema permitirá al administrador actualizar la información de los usuarios.
- El sistema permitirá al administrador desactivar y reactivar usuarios.

#### Seguridad
- El sistema permitirá al administrador enviar un correo de recuperación de contraseña a los usuarios.
- El sistema permitirá al administrador asignar permisos por módulo a los usuarios.

## Alcance técnico

- Autenticación basada en JWT.
- Manejo de roles y permisos (RBAC).
- Almacenamiento seguro de contraseñas (hashing).
- Envío de correos para recuperación de contraseña.