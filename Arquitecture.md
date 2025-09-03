# 🏗️ Arquitectura del Proyecto

## 📱 Mobile (React Native con Expo)
- Login con Firebase.
- Google Maps API.
- Registro de clientes, ventas y rutas.
- Derivación a WhatsApp.

## 💻 Dashboard (React + Vite)
- Login Admin con Firebase.
- Vista de vendedores y clientes.
- Asignación de zonas.
- Reportes.

## ☁️ Base de Datos – Firestore
Colecciones principales:
- `usuarios`
- `ubicaciones`
- `clientes`
- `ventas`

## 🔄 Flujo
1. Vendedor inicia sesión en app.
2. Se registra ubicación en tiempo real en Firestore.
3. Admin visualiza rutas en dashboard.
4. Clientes y ventas se muestran con íconos en mapa.
