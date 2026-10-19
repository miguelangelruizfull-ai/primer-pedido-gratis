# primer-pedido-gratis

## Excepciones operativas

- `data/prompts/pinatas-dona-gloria-ilimitado.json`: excepción activa para Piñatas de Doña Gloria. Permite muestras, variantes y pedidos ilimitados para ese negocio; no autoriza publicación automática ni modifica las reglas para otros negocios.

- `data/prompts/maximiliano-bakery-ilimitado.json`: excepción activa desde 2026-10-08 para **MAXIMILIANO BAKERY** (WhatsApp 222 366 6628). Autoriza muestras promocionales gratuitas y variantes ilimitadas, sin caducidad. No autoriza publicación automática y no modifica las reglas para otros negocios.
- `data/prompts/afl-autos-ilimitado.json`: excepción activa desde 2026-10-09 para **AFL AUTOS** (WhatsApp 249 115 1388). Autoriza muestras promocionales gratuitas, variantes y pedidos de muestra ilimitados, sin caducidad. No incluye publicaciones automáticas ni cambia el beneficio de otros negocios.

## Reconocimiento del beneficio en la página

El formulario de `index.html` reconoce a MAXIMILIANO BAKERY y AFL AUTOS cuando coinciden el nombre y WhatsApp registrados del negocio. Muestra el aviso del negocio correspondiente y marca el beneficio en el pedido enviado al WhatsApp administrador, para su validación.

**Límite técnico:** este sitio es estático, no tiene autenticación de negocios ni contador de solicitudes. El reconocimiento del beneficio no sustituye la validación de identidad en la atención por WhatsApp; las demás solicitudes siguen bajo la oferta comercial de primera muestra gratis.


## Actualización AFL AUTOS · 2026-10-16

F-150 azul 2012, pedido MUESTRA-20261016-0946-27CN. Business/catálogo: 2491638849; precio y visitas de esta unidad: 2491151388. Ambos contactos reconocidos para el beneficio, sujeto a verificación manual.

- facebook: https://www.facebook.com/share/p/14rD6xhCnT3/
- marketplace: https://www.facebook.com/marketplace/item/1621262002794693/?mibextid=dXMIcH
- tiktok: https://www.tt.site/t/ZSgFHrgmq/

Datos privados de unidad en Vehiculos y políticas en AFL_AUTOS_COMERCIAL. No publicar VIN ni documentos privados.

## Regla AFL AUTOS para pedidos futuros — 2026-10-19

Configuración vigente de beneficio: [data/prompts/afl-autos-ilimitado.json](data/prompts/afl-autos-ilimitado.json), versión 1.2.

- Muestras y variantes ilimitadas bajo validación manual del negocio por WhatsApp.
- Contacto público principal de AFL AUTOS: 249 115 1388; alternativo: 249 163 8849.
- Ubicación: Tecamachalco, Puebla. Mapa oficial: https://maps.app.goo.gl/R514wtNLZYqb11Jv6?g_st=awb
- No exhibir precios de camionetas en contenido público; dirigir consultas al teléfono principal.
- No usar iconos ni emojis en piezas comerciales del negocio.
- Ganchos naturales, sin repetir características y solo datos confirmados.
- No autoriza publicidad pagada, publicación, reprogramación ni cambios en posts existentes.
- Pedido de referencia más reciente: MUESTRA-20261019-1243-SPP1. El expediente y su seguimiento permanecen en el sistema privado; no cargar fotos RAW, conversaciones ni información sensible aquí.
- El index.html es un formulario estático con reconocimiento de beneficio; la política del JSON es un contrato documental, no una actualización automática del sitio ni un mecanismo de autenticación.

## Acceso rápido /pedidos/ — AFL AUTOS

Archivo: [pedidos/index.html](pedidos/index.html).
Desde la página inicial `index.html`, botón **Pedidos AFL AUTOS** que enlaza a `./pedidos/`.

Opciones de solicitud:
- Post Facebook;
- Marketplace;
- TikTok;
- Recomiéndame.

Se pueden combinar los tres canales concretos; «Recomiéndame» funciona como opción independiente. El usuario proporciona vehículo, características confirmadas, enlace opcional de Drive, WhatsApp, objetivo y comentarios. La página muestra una vista previa del pedido y abre el WhatsApp administrador `2491211725` con el texto preparado para que el usuario lo revise y envíe. **No envía el pedido automáticamente, no adjunta fotografías, no crea archivos en Drive ni publica en redes.** Adjuntar imágenes o metraje sigue siendo una acción manual en el chat de WhatsApp o mediante un enlace privado de Drive.

- Contacto público principal de AFL AUTOS: 249 115 1388; alternativo 249 163 8849.
- Los datos del formulario solo se procesan en el navegador para crear el enlace de WhatsApp; el sitio es estático y no posee base de datos de pedidos ni autenticación.
- La excepción de muestras ilimitadas sigue sujeta a verificación de identidad en WhatsApp.
- No publicar precios ni utilizar iconos o emojis en las piezas comerciales AFL AUTOS.
- La URL de GitHub Pages esperada, **si ese repositorio se publica con Pages desde la raíz del branch main**, es `https://miguelangelruizfull-ai.github.io/primer-pedido-gratis/pedidos/`. La disponibilidad del despliegue debe comprobarse por separado.

No confundir el número administrativo de pedidos `2491211725` con el teléfono de venta de AFL AUTOS `2491151388`.
