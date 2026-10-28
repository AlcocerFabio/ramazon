# RAMAZON · Tienda web

Thrift de tenis en Santa Cruz, Bolivia. **Un par. Una talla. Una vez.**

Sitio estático (un solo `index.html` + carpeta `img/`), listo para GitHub Pages.

## Cómo actualizar la tienda

Abre `index.html` y edita el bloque **EDITA AQUÍ** (cerca de la línea 440):

| Qué | Dónde |
|---|---|
| Número de WhatsApp (con 591 adelante) | `const WHATSAPP = "59167187879";` |
| Marcar vendidos | `const VENDIDOS = ["PROD-009", ...];` (agrega el código) |
| Pares destacados | `const DESTACADOS = [...]` |
| Punto de encuentro (Google Maps) | `const UBICACION = "..."` |

Guarda el cambio (commit) y en 1 o 2 minutos la página se actualiza sola.
