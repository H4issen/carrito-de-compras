# GuitarLA — Carrito de Compras para Tienda de Guitarras

¿Tienes una tienda de instrumentos y necesitas un carrito de compras rápido y funcional para tu web? Esta app muestra un catálogo de guitarras y permite a tus clientes armar su pedido al instante, sin recargar la página.

## ¿Qué hace?

Un escaparate digital con guitarras, precios y descripciones. Los clientes agregan productos al carrito, ajustan cantidades (hasta 5 por modelo) y ven el total actualizado. Todo desde una sola página, limpia y rápida.

## ¿Qué problemas resuelve?

| Sin carrito digital                          | Con GuitarLA                              |
|----------------------------------------------|-------------------------------------------|
| Tus clientes preguntan precios uno por uno   | Ven todo el catálogo con precios claros   |
| Anotas pedidos en papel                      | El cliente arma su propio carrito         |
| Sin control de cantidad en el pedido         | Límite de 5 unidades por producto         |
| Dificultad para modificar un pedido          | Suma o resta cantidad con un clic         |

## Posibles mejoras futuras

- Catálogo editable desde un panel de administración
- Procesar pedido con formulario de datos del cliente
- Integración con pasarela de pago (PayPal, Mercado Pago)
- Envío de resumen del pedido por WhatsApp o email
- Galería de imágenes por producto
- Modo oscuro y personalización de marca

## Stack técnico

React 18 + Vite. Sin dependencias extras. Rápido, liviano y desplegable en GitHub Pages.

```bash
npm install
npm run dev      # desarrollo
npm run deploy   # publicar
