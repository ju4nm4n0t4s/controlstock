# Project Scope — Inventario y Ventas (MVP)

## Objetivo
Crear una aplicación web simple para gestionar el inventario de productos (sabores de helado) y permitir a los distribuidores registrar pedidos con validación automática de stock.


## Usuarios
- Distribuidor: consulta stock disponible y crea pedidos.
- Administrador: gestiona inventario y supervisa pedidos.
- (Futuro) Gestión completa de usuarios y reportes.

## Funcionalidades (MVP — Fase 1: UI)
- Login básico (estructura visual).
- Ver resumen (tarjetas KPI): productos, stock total, pedidos del día.
- Vista para creación de pedido (carrito visual).
- Vista de inventario (tabla con datos de ejemplo).
- Interfaz para registrar producción (solo interfaz, sin lógica aún).

## Fase 2 (JavaScript)
- Agregar/editar/eliminar productos (en memoria y/o LocalStorage).
- Creación de pedidos con validación automática.
- Estado del pedido:
  - Confirmed
  - NeedsAction
- Persistencia en memoria y/o LocalStorage.
- Búsqueda y filtros por nombre/categoría.
- Validaciones y mensajes amigables (errores/éxito).

## Fase 3 (React + Firebase)
- Autenticación (roles).
- Base de datos en Firestore.
- Historial de pedidos.
- Gestion de usuarios
- Despliegue (Vercel/Firebase Hosting).

## Pantallas (inicial)
- Login
- Módulo Inventario (Admin)
- Módulo Pedido (Distribuidor)

En la primera fase se desarrollará la estructura visual completa antes de implementar lógica.