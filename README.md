# ChumBlum Distribuidores

Aplicación web para la gestión de inventario y pedidos del emprendimiento Helados Chum Blum.

Proyecto académico desarrollado bajo una metodología incremental orientada al desarrollo progresivo (HTML → CSS → JavaScript → React → Firebase).

---

## 📌 Descripción

ChumBlum Distribuidores es una aplicación web diseñada para administrar el stock de sabores y permitir a los distribuidores crear pedidos con validación automática de inventario.

El sistema busca reemplazar el uso de hojas de cálculo compartidas y la validación manual vía WhatsApp, proporcionando un flujo más eficiente y controlado.

En la fase actual se desarrolla:

- Estructura semántica utilizando HTML5.
- Sistema de estilos organizado con CSS3.
- Documentación técnica dentro de la carpeta `docs/`.
- Base preparada para futuras fases con JavaScript, React y Firebase.

---

## 🏗 Metodología de Desarrollo

El proyecto se desarrolla de manera incremental por fases:

### Fase 1 — Estructura y Diseño (Actual)
- HTML semántico.
- CSS modular.
- Definición del sistema de diseño.
- Documentación técnica en `docs/`.

### Fase 2 — Interactividad
- JavaScript (ES6).
- Manipulación del DOM.
- Validación automática de stock.
- Gestión dinámica de pedidos.
- Persistencia en LocalStorage.

### Fase 3 — Componentización
- Migración a React.
- Organización en componentes reutilizables.
- Manejo de estado y rutas.

### Fase 4 — Backend as a Service
- Firebase Authentication (roles).
- Firestore como base de datos.
- Persistencia real de inventario y pedidos.
- Despliegue en hosting profesional.

---

## 📂 Estructura del Proyecto

chumblum-distribuidores/

├── assets/ # Recursos estáticos (imágenes, iconos)  
├── css/  
│   └── styles.css # Hoja de estilos principal  
├── docs/  
│   ├── project_scope.md  
│   ├── design_system.md  
│   └── tech_stack.md  
├── pages/ # Vistas internas (admin, distribuidor)  
├── index.html # Login (punto de entrada)  
├── .gitignore  
└── README.md  

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/TU-USUARIO/chumblum-distribuidores.git