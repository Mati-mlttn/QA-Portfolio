# Test Plan - Rescuetrack 2024

## Objetivo

Validar el funcionamiento de los módulos principales del sistema Rescuetrack en sus dos plataformas: autenticación y control de acceso por rol, gestión de usuarios y vehículos, mantenciones, notificaciones y reportes de costos, incluyendo la correcta sincronización de datos entre la app móvil y la web.

**Aplicación bajo prueba:** Rescuetrack — sistema de gestión de vehículos de emergencia (login, gestión de usuarios y vehículos, mantenciones, notificaciones y reportes de costos), con versión web y móvil

**Tipo de testing:** Funcional, Integración, Carga y Stress — caja negra

**Entorno:** Web + Móvil · Proyecto académico en equipo

## Alcance

**Web**

- Login: credenciales válidas e inválidas, expiración de sesión, control de acceso por rol
- Registro y gestión de usuarios: alta, edición y eliminación, validación de campos y formato de correo institucional
- Vehículos: alta, edición, eliminación, filtrado, visualización, prueba de carga (700 vehículos) y stress (700 actualizaciones simultáneas)
- Reportes de costos y mantención: visualización, datos incompletos, exportación exitosa y manejo de errores

**Móvil**

- Login: credenciales válidas, campos obligatorios vacíos, datos incorrectos, pruebas de carga y stress
- Vehículos: búsqueda, gestión de mantenciones (agregar, editar, cancelar), datos incompletos, sincronización con la versión web, pruebas de carga y stress
- Notificaciones: acceso a la sección y recordatorios de mantención programada
- Costos: visualización, actualización de datos y exportación en PDF (éxito y sin datos disponibles)
