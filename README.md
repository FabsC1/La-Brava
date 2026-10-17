# La Brava

Página web de una sola página para **La Brava**, una hamburguesería con hamburguesas artesanales, batidos y complementos.

## Ver la página

Abre `index.html` en un navegador para verla localmente. La página usa Tailwind CSS y fuentes de Google Fonts mediante CDN, así que necesitas conexión a internet para que carguen esos recursos.

## Publicar en GitHub Pages

1. Sube `index.html` a la raíz de este repositorio.
2. Abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/ (root)`.
5. Pulsa **Save**. GitHub mostrará la dirección de la página en esa misma sección.

## Pedidos por WhatsApp

Los enlaces de pedido están configurados para el número `+51 999 888 777`. Cada producto abre WhatsApp con un mensaje que incluye su nombre; el botón flotante permite enviar una consulta general.

Para cambiar el número, actualiza `WHATSAPP_NUMBER` en el código de `index.html` y revisa los enlaces `wa.me` del encabezado y del botón flotante.

## Personalizar antes de publicar

- Cambia los precios y descripciones de ejemplo por los datos reales.
- Actualiza el horario, la ubicación y los enlaces de redes sociales.
- Sustituye las fotografías de Unsplash si tienes imágenes propias.
- Verifica en WhatsApp que el número de pedidos sea correcto.

## Tecnologías

- HTML5
- Tailwind CSS por CDN
- JavaScript vanilla
- Imágenes de Unsplash
