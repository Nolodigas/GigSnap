# GigSnap 🎸 v3.0

Aplicación web para buscar conciertos y festivales en España con parsing inteligente.

## Características

- Búsqueda optimizada (DuckDuckGo)
- Detección automática de eventos
- Parsing avanzado:
  - JSON-LD (schema.org/Event)
  - OpenGraph
  - HTML fallback
- Auto actualización
- Persistencia local

## Pipeline

1. URL directa
2. JSON-LD parsing
3. OpenGraph
4. HTML scraping

## Tecnología

- HTML + JS puro
- Sin backend
- CORS proxy

## Limitaciones

- Algunas webs bloquean scraping
- Dependencia de estructura externa

## Deploy

Subir a GitHub Pages directamente.