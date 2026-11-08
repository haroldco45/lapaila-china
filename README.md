# La Paila China — App (PWA)

Menú digital con pedidos por WhatsApp para **La Paila China**, cocina casera y arroz chino
(Cl. 11a #21-68, Barrio El Triángulo, Caucasia, Antioquia · Instagram @lapaila_china).

## Qué trae
- Portada con fotos reales que rotan y estado **Abierto / Cerrado** con la hora real de Colombia (America/Bogota).
- Sección **Hoy**: plato del día según el día de la semana, horario de hoy y cuánto falta para cerrar.
- Menú por categorías: Almuerzos, Porciones, Arroz chino, Desayunos, Siempre disponibles.
- **Arma tu almuerzo**: proteína + sopa opcional (seco $15.000, completo desde $20.000).
- Carta real: porciones, arroz chino por tamaño, chop suey, combos de pollo y desayunos armables.
- Pedido por WhatsApp: en el local, recoger (anticipo 50 %) o domicilio por zona ($4.000 a $8.000); efectivo, transferencia, QR o tarjeta, y factura.
- Español e inglés.
- Panel **Administrar menú** (al pie, clave `1234`): WhatsApp del restaurante y proteínas agotadas del día.
- Instalable (manifest + service worker) y vista previa del enlace (Open Graph).

## Antes de publicar
1. Poner el WhatsApp del restaurante en `CONF.wa` dentro de `index.html` (formato `57300…`).
2. Confirmar precios con el restaurante (constantes `PROT`, `SOPAS`, `MENU`, `ZONAS`).

## Publicar
Repo `haroldco45/lapaila-china` → Netlify: https://lapaila-china.netlify.app

Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados · vibraspositivashm.com
