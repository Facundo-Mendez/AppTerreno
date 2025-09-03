  # 📌 App de Terreno – Control de Vendedores

Este proyecto es una aplicación móvil y un panel web para **gestionar vendedores en terreno**, permitiendo:
- Seguimiento de ubicación en tiempo real.
- Registro de clientes y ventas en mapa (Google Maps).
- Asignación de zonas de venta.
- Derivación a WhatsApp para comunicación con clientes.
- Dashboard web para administradores con reportes y control de recorridos.

---

## 🚀 Tecnologías principales
- **Mobile (App Vendedores):** React Native (Expo), Firebase, Google Maps API
- **Dashboard (Web Admin):** React (Vite), Firebase Auth + Firestore
- **Backend / DB:** Firebase Firestore (y Authentication)

---

## 🏗️ Estructura del Proyecto
- `/mobile` → Aplicación móvil (Expo).
- `/dashboard` → Panel web (React + Vite).
- `/docs` → Documentación técnica y arquitectura.

---

## 🌳 Flujo de Ramas (Git)
- `main`: código estable y en producción.
- `develop`: rama base de integración.
- `feature/<nombre>`: nuevas funcionalidades.
- `bugfix/<nombre>`: corrección de errores.
- `release/vX.Y.Z`: preparación de versiones.
- `hotfix/<nombre>`: correcciones urgentes en producción.

---

## 📋 Convenciones de Commits
Usamos el formato:  
<Tipo>: Descripcion breve

Ejemplos:
- `feat: agregar login con Firebase`
- `fix: corregir error en tracking de ubicación`
- `docs: actualizar README`

Tipos principales: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.
