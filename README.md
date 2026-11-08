# KEN BARBER — Sitio web

Sitio web responsivo en HTML, CSS y JavaScript, sin dependencias de compilación.

## Abrir en Visual Studio Code

1. Descomprime `ken-barber-web.zip`.
2. En Visual Studio Code selecciona **Archivo > Abrir carpeta** y abre `ken-barber`.
3. Abre `index.html` con la extensión **Live Server** (opcional) o haz doble clic en el archivo para verlo en tu navegador.
4. Para publicarlo, sube `index.html`, `styles.css`, `script.js` y la carpeta `assets` a tu hosting, Netlify o GitHub Pages.

## Reservaciones

El formulario **NO bloquea horarios ni guarda reservas**. Genera un mensaje con los datos de la solicitud y abre WhatsApp al +504 3313-3822. La barbería confirma manualmente la disponibilidad. Los horarios mostrados son intervalos sugeridos de 30 minutos dentro del horario comercial, no disponibilidad en tiempo real.

Para citas confirmadas automáticamente, agenda compartida y prevención de doble reserva, se requiere integrar un backend o servicio de calendario/reservaciones.

## Datos utilizados

- Marca: Ken Barber.
- Teléfono y WhatsApp: +504 3313-3822.
- Ubicación: Tegucigalpa, Honduras (dirección exacta pendiente).
- Horarios: lunes-viernes 9:00–19:00, sábado 8:00–18:00, domingo 10:00–16:00.
- Corte de niño: L 200; corte + diseño: L 220.
- Corte y barba: precio por confirmar (se agregó como servicio ilustrativo, no como tarifa confirmada).
- Fotografías: imágenes suministradas por el usuario.

## Personalización

- Colores: variables CSS en `:root` de `styles.css`.
- Precios, textos, servicios y horarios visibles: `index.html`.
- Horarios que aparecen en el formulario: `updateTimes()` en `script.js`. Mantenerlos sincronizados con `index.html`.
- Número de WhatsApp: constante `PHONE` en `script.js`, enlaces en `index.html`.
- Dirección exacta: reemplazar la ubicación genérica y enlace de Google Maps en `index.html` cuando se conozca.

## Aviso

Las imágenes fueron recortadas de las fotografías compartidas, eliminando franjas negras de las capturas. Las fuentes se cargan desde Google Fonts; si no hay internet, el navegador usará fuentes alternativas.
