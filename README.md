# primer-pedido-gratis

## Excepciones operativas

- `data/prompts/pinatas-dona-gloria-ilimitado.json`: excepción activa para Piñatas de Doña Gloria. Permite muestras, variantes y pedidos ilimitados para ese negocio; no autoriza publicación automática ni modifica las reglas para otros negocios.

- `data/prompts/maximiliano-bakery-ilimitado.json`: excepción activa desde 2026-10-08 para **MAXIMILIANO BAKERY** (WhatsApp 222 366 6628). Autoriza muestras promocionales gratuitas y variantes ilimitadas, sin caducidad. No autoriza publicación automática y no modifica las reglas para otros negocios.

## Reconocimiento del beneficio en la página

El formulario de `index.html` reconoce a MAXIMILIANO BAKERY cuando coinciden el nombre y WhatsApp del negocio. Muestra un aviso y marca el beneficio en el pedido enviado al WhatsApp administrador, para su validación.

**Límite técnico:** este sitio es estático, no tiene autenticación de negocios ni contador de solicitudes. El reconocimiento del beneficio no sustituye la validación de identidad en la atención por WhatsApp; las demás solicitudes siguen bajo la oferta comercial de primera muestra gratis.
