# Checkout UX/UI · White Label

Flujo de checkout white-label de 3 pasos, diseñado y prototipado por **Ticiana Paura**.

🔗 **Demo en vivo:** https://ticianapaura.github.io/checkout-ux-ui/

## El flujo

1. **Método** – grilla de métodos de pago (tarjeta, transferencias, billeteras).
2. **Monto** – selección entre tarjetas guardadas con carrusel y validación de CVV.
3. **Confirmación** – resumen del pago con su ID de transacción.

## Decisiones de diseño

- **White label:** la marca (nombre, logo, email de soporte) vive en un solo archivo de configuración, así un comercio nuevo solo cambia eso.
- **Design tokens:** colores, tipografía y espaciados definidos como variables CSS.
- **Accesibilidad:** el foco se mueve al título de cada pantalla al avanzar, para usuarios de teclado y lectores de pantalla.
- **Componentes:** stepper, tiles de método, tarjeta guardada, campo CVV, tooltip, toast y control segmentado.

## Stack

React · TypeScript · Vite · CSS Modules
