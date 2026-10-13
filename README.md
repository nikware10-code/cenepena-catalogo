# cenepena-catalogo

Catalogo web de Grupo Cenepena S.L. (Madrid) - distribuidora mayorista de alimentos latinos.
Los pedidos se envian por WhatsApp; no hay carrito de pago ni backend.

## Archivos

- `index.html` - diseno, estilos y logica. No se toca para cambiar productos.
- `productos.js` - `WA` (WhatsApp), `CATS` (categorias) y `PRODUCTS`. **Aqui se edita el catalogo.**
- `img/<id>.jpg` - una foto por producto, mas `logo.jpg`. El `id` del producto es el nombre del archivo.

## Como actualizar

1. Subir primero las fotos nuevas a `img/`.
2. Despues `productos.js` (y `index.html` si cambia el diseno).

`index.html` y `productos.js` deben ir siempre juntos: si solo sube uno, la web queda rota hasta que llegue el otro.

Cada commit en `main` dispara el despliegue en Cloudflare (~1-2 min).
