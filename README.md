# GigSnap 🎸 · by Nolodigas

> Tu agenda musical inteligente — Gestiona conciertos y festivales con IA

**GigSnap** es una app web que funciona directamente en el navegador (sin instalación) y se puede publicar gratis en GitHub Pages. Diseñada para ser ultra intuitiva — perfecta para compartir con amigos y familia.

---

## ✨ Características

### 🔍 Búsqueda inteligente con IA
- Escribe el nombre de un concierto o festival
- La IA busca en internet la información oficial: fecha, lugar, artistas, precio, enlace de entradas
- Con un toque lo añades a tu agenda

### 🎪 Gestión de eventos
- Añade conciertos y festivales (con búsqueda IA o manualmente)
- Cuenta atrás en tiempo real al próximo evento
- Badges visuales: 🔥 HOY / ⚡ En X días / Pasado
- Vista calendario con puntos en días con eventos
- Compartir por WhatsApp con texto formateado

### 💰 Control de gastos
- Categorías: 🎫 Entrada · 🏨 Alojamiento · 🚗 Transporte · 🍔 Comida · 👕 Merch · 💰 Otros
- Resumen global con gráfico de barras por categoría y por evento
- Total gastado en todos tus eventos

### 📎 Adjuntar entradas
- Drag & drop o selector de archivo
- Imagen (foto de la entrada) o PDF (e-ticket)
- Visor integrado

### 📅 Exportar al calendario
- Descarga el evento en formato .ics (compatible con Google Calendar, Apple Calendar, Outlook)
- Incluye recordatorios automáticos: 1 día antes y 2 horas antes

---

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub llamado `gigsnap`
2. Sube el archivo `index.html`
3. Ve a **Settings → Pages → Branch: main → Save**
4. En 1-2 minutos la app estará en: `https://tuusuario.github.io/gigsnap`

---

## 🔑 Configurar la búsqueda IA

La primera vez que abras la app te pedirá una clave API de Anthropic. Pasos:

1. Ve a [console.anthropic.com](https://console.anthropic.com/settings/keys)
2. Crea una cuenta (hay créditos gratuitos de inicio)
3. En **API Keys → Create Key**, crea una nueva clave
4. Pégala en la app cuando te la pida

La clave se guarda solo en tu dispositivo (localStorage) y nunca sale de él.  
Una vez configurada, todos los que usen la app desde ese dispositivo tendrán búsqueda IA activa.

> Si no quieres configurar la IA, puedes añadir eventos manualmente sin problema.

---

## 🎨 Diseño

Sigue el Brand System Nolodigas v1.0:
- **Tipografía:** Fraunces (títulos) + Nunito (interfaz, mín 17px en móvil)
- **Gradiente firma:** `linear-gradient(135deg, #5629FF → #8B2FE8 → #FF4D20)`
- **Fondo:** `#F5F2FF` (Nolodigas Pearl)
- **Acento:** `#5629FF` Violet / `#FF4D20` Coral / `#FFD04D` Gold

---

## 📱 Compatibilidad

- ✅ Chrome, Safari, Firefox, Edge (móvil y escritorio)
- ✅ iOS (añadir a pantalla de inicio → funciona como app nativa)
- ✅ Android (instalar como PWA)
- ✅ GitHub Pages, Netlify, Vercel — cualquier hosting estático

---

*GigSnap · by Nolodigas · v2.0*
