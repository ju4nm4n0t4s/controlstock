# Tech Stack - ChumBlum Distribuidores

## Objetivo Tecnológico

Desarrollar una aplicación web progresiva que evolucione de una estructura estática (HTML y CSS) hacia una aplicación fullstack utilizando React y Firebase, siguiendo la secuencia del curso de formación.

El enfoque será incremental, permitiendo validar primero la experiencia visual, luego la lógica de negocio en frontend y finalmente la persistencia en la nube.

---

# Roadmap de Implementación

## Fase 1: HTML + CSS (Estructura Visual)

- Maquetación de las pantallas principales:
  - Login
  - Administración de Inventario
  - Creación de Pedido (Distribuidor)
- Implementación del sistema de diseño (colores, tipografía, componentes).
- Navegación básica entre páginas.
- Diseño Mobile First.

Objetivo: Validar experiencia visual y estructura del sistema.

---

## Fase 2: JavaScript (Lógica en Frontend)

- Manejo de datos en memoria (arrays).
- Persistencia temporal con LocalStorage.
- Validación automática de stock.
- Implementación de estados del pedido:
  - Draft
  - NeedsAction
  - Confirmed
- Mensajes de validación amigables.
- Actualización dinámica del inventario.

Objetivo: Tener un MVP completamente funcional sin backend.

---

## Fase 3: React (Componentización)

- Migración de la interfaz a React.
- Separación en componentes reutilizables:
  - Login
  - Tabla de Stock
  - Carrito
  - Lista de Pedidos
- Manejo de estado con hooks.
- Implementación de rutas (React Router).

Objetivo: Mejorar mantenibilidad y escalabilidad de la aplicación.

---

## Fase 4: Firebase (Backend as a Service)

- Firebase Authentication (login por roles).
- Firestore como base de datos.
- Persistencia real de:
  - Usuarios
  - Productos
  - Pedidos
- Despliegue en Firebase Hosting.

Objetivo: Convertir el proyecto en una aplicación fullstack real.

---

# Tecnologías Utilizadas

## Frontend Inicial
- HTML5
- CSS3
- JavaScript (Vanilla)
- Diseño Mobile First

## Control de Versiones
- Git
- GitHub

## Framework (Fase 3)
- React

## Backend (Fase 4)
- Firebase Authentication
- Firebase Firestore

---

# Principios Técnicos

- Desarrollo incremental por fases.
- Separación entre estructura, lógica y persistencia.
- Validación de reglas de negocio antes de integrar backend.
- Evolución progresiva sin rehacer el proyecto.