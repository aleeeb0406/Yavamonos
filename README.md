# Yavamonos

Prototipo de app de pedidos anticipados para cafeterías escolares de la UABC: pides desde el salón, pagas en la app y recoges con un código QR en una zona de pick-up exclusiva.

## Cómo abrirlo

- **En línea:** si GitHub Pages está activado, entra a `https://<tu-usuario>.github.io/<nombre-del-repo>/`.
- **En tu computadora:** descarga el repositorio y abre `yavamonos-app.html` en el navegador. No necesita instalación ni servidor.

## Qué incluye

- Elegir campus (Mexicali, Tijuana, Ensenada), buscar y filtrar cafeterías y platillos.
- Personalizar platillos (salsa, tamaño, extras, instrucciones) y armar el carrito.
- Elegir horario de recolección y forma de pago.
- Seguimiento del pedido en tiempo real (simulado) y código QR real para recoger.
- Favoritos, historial de pedidos y perfil.

Funciona en celular y en laptop. Los datos de cafeterías, platillos y usuario son ficticios.

## Archivos

| Archivo | Contenido |
|---|---|
| `yavamonos-app.html` | Toda la app: HTML, CSS y JavaScript en un solo archivo |
| `logo_yavamonos.png` | Logo |
| `img/` | Fotos de cafeterías y platillos, nombradas con el id de cada uno |
| `index.html` | Redirige a la app (para GitHub Pages) |

### Agregar o cambiar fotos

1. Guarda la imagen en `img/` con el id del platillo o cafetería: `img/torta-asada.jpg`.
2. Agrega ese id a la lista `FOTOS` al inicio del script en `yavamonos-app.html`.

Si falta una foto, la app muestra un placeholder.

## Diseño

- Paleta: navy `#14274E`, lima `#D9E154` y blanco, con neutros derivados.
- Tipografías: Sora (títulos) e Inter (texto).
- Contraste AA, objetivos táctiles de 44 px, navegación con teclado y soporte para movimiento reducido.
