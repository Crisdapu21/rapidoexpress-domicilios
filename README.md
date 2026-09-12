# RápidoExpress · Prototipo de página de domicilios

Prototipo navegable de alta fidelidad para una **empresa de domicilios**, desarrollado como parte de la **Actividad de Construcción Aplicada (ACA)** de la asignatura **Ingeniería Web** — Corporación Unificada Nacional de Educación Superior (CUN), programa de Ingeniería de Sistemas.

## 🔗 Enlace en vivo (prototipo navegable)

- **Prototipo (alta fidelidad):** https://crisdapu21.github.io/rapidoexpress-domicilios/
- **Wireframe (baja fidelidad):** https://crisdapu21.github.io/rapidoexpress-domicilios/wireframe/

> El prototipo es completamente navegable e interactivo (buscar, filtrar, agregar al carrito, favoritos, checkout, seguimiento del pedido, inicio de sesión y cuenta). No requiere instalación: se ejecuta en el navegador.

## 🧭 Flujos principales

1. **Inicio** → categorías + restaurantes populares.
2. **Explorar** → búsqueda con filtros (envío gratis, calificación, tiempo) y ordenamiento.
3. **Detalle del restaurante** → menú por categorías, agregar al carrito, guardar en favoritos.
4. **Carrito** → editar cantidades y ver resumen.
5. **Checkout** → dirección con mapa, domicilio/recoger, método de pago (Tarjeta, PSE, Nequi, Efectivo).
6. **Seguimiento** → línea de tiempo del pedido y repartidor en el mapa (tiempo real simulado).
7. **Cuenta** → mis pedidos, favoritos, direcciones, métodos de pago, perfil y privacidad.

## ✅ Requerimientos cubiertos

**Funcionales:** RF1 Gestión de pedidos · RF2 Gestión de usuarios · RF3 Procesamiento y entrega · RF4 Pagos · RF5 Localización.

**No funcionales:** RNF1 Rendimiento (un solo archivo, sin dependencias pesadas) · RNF2 Escalabilidad (arquitectura por componentes/datos) · RNF3 Seguridad y privacidad (2FA, controles de datos, pago cifrado) · RNF4 Experiencia de usuario (diseño centrado en el usuario, accesible) · RNF5 Compatibilidad con dispositivos (responsive + tema claro/oscuro).

## 🛠️ Tecnología

HTML5 + CSS3 (variables, grid/flex, tema claro/oscuro) + JavaScript (vanilla, SPA con enrutado por hash). Tipografías: Bricolage Grotesque + Manrope (Google Fonts). Sin frameworks ni backend.

## 📁 Estructura

```
index.html            → Prototipo de alta fidelidad (mockup navegable)
wireframe/index.html  → Wireframe de baja fidelidad
```

---

Autoría: Cristian David Pulido Sarmiento — Ingeniería de Sistemas, Grupo 53329. Docente: Sergio Alexander Mora Novoa. ACA Ingeniería Web (CUN), 2026. Uso académico.
