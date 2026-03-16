# 💰 TiqueTracker - PWA de Finanzas Personales

**Clasificá tus tiquetes por rubro con IA y exportá a Excel.**  
Hecho en Costa Rica · Ecosistema ODISEO

---

## 📲 Instalación en Android (1 click)

### Opción A: GitHub Pages (gratis, recomendado)

1. Creá un repositorio en GitHub (ej: `tiquetracker`)
2. Subí **todos los archivos** de esta carpeta al repositorio
3. Andá a **Settings → Pages → Source: main → / (root) → Save**
4. Esperá 1-2 minutos. Tu app estará en: `https://TU-USUARIO.github.io/tiquetracker/`
5. Abrí esa URL en Chrome (Android) → aparecerá el banner **"Instalar TiqueTracker"**
6. ¡Toqué **Instalar** y listo! Se agrega a tu pantalla de inicio como app nativa

### Opción B: Netlify (gratis, más fácil)

1. Andá a [netlify.com](https://netlify.com) y creá una cuenta gratis
2. Arrastrá la carpeta completa al área de deploy
3. Netlify te da una URL tipo `https://TU-SITIO.netlify.app`
4. Abrí en Chrome (Android) → Instalar

### Opción C: Cualquier hosting con HTTPS

Subí los archivos a cualquier servidor con HTTPS. Las PWA requieren HTTPS para instalarse.

---

## 🏗 Estructura de archivos

```
tiquetracker/
├── index.html          ← App principal (HTML + JS + CSS todo en uno)
├── manifest.json       ← Configuración PWA (nombre, iconos, colores)
├── sw.js              ← Service Worker (cache offline)
├── README.md          ← Este archivo
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

---

## ✨ Funcionalidades

- **📷 Escaneo con IA** — Tomá foto del tiquete, Claude extrae datos automáticamente
- **✏️ Ingreso manual** — Formulario rápido con clasificación IA
- **🤖 Clasificación automática** — La IA sugiere el rubro según el gasto
- **⚙️ Rubros personalizables** — 10 predeterminados + los que vos querás
- **📋 Tabla interactiva** — Filtros, edición y eliminación
- **📊 Gráficos** — Donut de distribución + barras por rubro
- **📥 Descarga Excel** — Exporta CSV compatible con Excel
- **💾 Datos locales** — Todo se guarda en tu teléfono (localStorage)
- **📱 Instalable** — Se instala como app nativa en Android

---

## 🔒 Privacidad

- Todos los datos se guardan **localmente** en tu dispositivo
- Las fotos de tiquetes se procesan con la API de Claude pero **no se almacenan**
- No hay servidor ni base de datos externa

---

## ⚡ Requisitos

- Navegador Chrome (Android) o Safari (iOS)
- Conexión a internet (solo para la clasificación con IA)
- La app funciona offline para ingreso manual y consultas

---

*TiqueTracker · Ecosistema ODISEO · 2026*
