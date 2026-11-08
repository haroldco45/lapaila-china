# La Paila China — App (PWA)

Menú digital con pedidos por WhatsApp para **La Paila China**, cocina casera y arroz chino
(Cl. 11a #21-68, Barrio El Triángulo, Caucasia, Antioquia · Instagram @lapaila_china).

## Qué trae
- Portada con fotos reales que rotan y estado **Abierto / Cerrado** con la hora real de Colombia (America/Bogota).
- Sección **Hoy**: plato del día según el día de la semana, horario de hoy y cuánto falta para cerrar.
- Menú por categorías: Almuerzos, Porciones, Arroz chino, Desayunos, Siempre disponibles.
- **Arma tu arroz chino**: tamaño, proteínas y acompañantes con precio en vivo.
- Pedido por WhatsApp: recoger (anticipo 50 %), en mesa o domicilio ($5.000), pago en efectivo, transferencia, QR o tarjeta, y opción de factura.
- Español e inglés.
- Panel **Administrar menú** (al pie, clave inicial `1234`): WhatsApp del restaurante, valor del domicilio, plato de cada día y precios.
- Instalable (manifest + service worker) y vista previa del enlace (Open Graph).

## Antes de publicar
1. Poner el WhatsApp del restaurante en `BASE.wa` dentro de `index.html` (formato `57300…`).
2. Cambiar los precios de ejemplo por los reales en `BASE.platos` y `ARMADOR`.

## Publicar
Repo `haroldco45/lapaila-china` → Netlify: https://lapaila-china.netlify.app

Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados · vibraspositivashm.com
