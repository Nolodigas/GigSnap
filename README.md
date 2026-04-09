# GigSnap 🎸 · by Nolodigas

**[→ Abrir app](https://nolodigas.github.io/gigsnap)**

Tu agenda musical inteligente — busca conciertos y festivales en España, guarda entradas, controla gastos y compártelo todo con tus amigos.

---

## Qué puedes hacer

- **Buscar con IA** — escribe el nombre del evento y GigSnap obtiene fecha, lugar, artistas, precio y enlace de entradas directamente de la web oficial
- **Pegar URL directamente** — si tienes el enlace oficial, pégalo en el buscador y extrae todos los datos automáticamente
- **Gestionar tus eventos** — próximos, vividos, con cuenta atrás en tiempo real
- **Adjuntar entradas** — foto, PDF o Apple Wallet (.pkpass) · hasta 5 archivos por evento
- **Controlar gastos** por categoría: entrada, alojamiento, transporte, comida, merch y otros
- **Compartir por WhatsApp** con fecha, lugar, artistas y enlace de entradas en un solo mensaje
- **Exportar al calendario** en formato .ics (Google Calendar, Apple Calendar, Outlook)
- **Ver resumen global** de todos tus gastos musicales con gráfico por categoría y evento

---

## Cómo funciona la búsqueda

1. Escribe el nombre del evento o pega la URL oficial
2. La app prioriza la web oficial del evento y sus páginas de entradas
3. Extrae y normaliza: nombre, tipo, fecha, hora, puertas, recinto, ciudad, descripción, artistas, web y enlace de entradas
4. La fuente detectada se reutiliza para actualizaciones automáticas futuras

El parser funciona en dos capas:
- **JSON-LD** (schema.org) — cuando la web del evento lo incluye, extracción directa y fiable
- **Heurístico** — para el resto de webs, análisis inteligente del contenido

---

## Almacenamiento

Todo se guarda en tu dispositivo, nunca en un servidor externo:
- Eventos, gastos, notas y archivos adjuntos
- Caché de búsquedas (evita repetir consultas)
- Clave API (solo en tu dispositivo)

---

## Actualización automática de eventos

La app revisa los eventos próximos al abrirse y mientras permanece abierta. También puede forzarse desde **Ajustes → Actualizar**.

---

*GigSnap · by Nolodigas · v2.5*
