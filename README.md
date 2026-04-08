# GigSnap 🎸 · by Nolodigas

Aplicación web estática para buscar conciertos y festivales en España, guardar entradas, controlar gastos y mantener los datos actualizados desde el propio navegador.

## Mejoras de esta versión

- Búsqueda afinada para conciertos y festivales en España.
- Prioridad reforzada a webs oficiales y páginas de entradas relevantes.
- Limpieza de metadatos Markdown para evitar texto basura en artistas, descripción o enlaces.
- Búsqueda más rápida con menos consultas, candidatos mejor filtrados y caché local.
- Actualización automática de eventos guardados reutilizando la fuente pública detectada.
- Datos guardados en el propio dispositivo del usuario.

## Cómo funciona la búsqueda

1. El usuario escribe el nombre del evento, añade una provincia opcional o pega la URL oficial.
2. GigSnap prioriza dominios que encajan con el evento y resultados públicos en España.
3. Extrae y normaliza:
   - nombre
   - tipo de evento
   - fecha y fecha fin
   - hora y apertura de puertas
   - recinto
   - ciudad
   - descripción
   - artistas
   - web oficial
   - enlace de entradas
4. La referencia detectada se reutiliza para futuras actualizaciones automáticas.

## Almacenamiento local

GigSnap guarda en el navegador del dispositivo:

- eventos
- gastos
- notas
- adjuntos en base64
- caché de búsquedas
- fuente pública asociada a cada evento

Claves usadas:

- `gigsnap_events`
- `gigsnap_search_cache`

## Actualización automática

- La app revisa los próximos eventos al abrirse.
- Mientras la página siga abierta, vuelve a comprobarlos periódicamente.
- También puede forzarse desde **Ajustes → Actualizar**.

## Publicación en GitHub Pages

1. Sube `index.html` y `README.md` al repositorio.
2. Ve a **Settings → Pages**.
3. Selecciona la rama principal.
4. Publica.

## Limitaciones reales

- Depende de que exista una página pública legible del evento.
- Algunas webs pueden cambiar su estructura y requerir ajustes futuros.
- La actualización automática solo ocurre mientras la app está abierta.
- `localStorage` tiene límite de espacio, por lo que no conviene acumular demasiados adjuntos pesados.

## Versión

**v2.3**
