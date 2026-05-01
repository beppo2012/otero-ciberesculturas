# Alejandro Otero — Ciber Esculturas 1987–2025

Exposición virtual de las 13 ciber esculturas de Alejandro Otero, creadas en el Centro Científico de IBM de Venezuela en 1987. Reconstruidas en realidad aumentada, 2025.

Producción y curaduría: **Ana Blanco**

---

## Cómo publicar este sitio en GitHub Pages (gratis)

### Paso 1 — Crear cuenta en GitHub
1. Ve a [github.com](https://github.com)
2. Crea una cuenta gratuita si no tienes una
3. Elige un nombre de usuario — ese nombre aparecerá en la URL del sitio

### Paso 2 — Crear el repositorio
1. Haz clic en el botón verde **"New"** (o el símbolo `+` arriba a la derecha)
2. Nombre del repositorio: `otero-ciberesculturas`
3. Selecciona **Public**
4. Haz clic en **"Create repository"**

### Paso 3 — Subir los archivos
1. En la página del repositorio vacío, haz clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos y carpetas de esta carpeta:
   - `index.html`
   - `aurea.html`
   - carpeta `img/` (con todas las imágenes)
   - carpeta `ar/` (con los archivos .usdz)
3. Escribe un mensaje: `Primera versión — Aurea`
4. Haz clic en **"Commit changes"**

### Paso 4 — Activar GitHub Pages
1. Ve a **Settings** (pestaña superior del repositorio)
2. En el menú izquierdo, haz clic en **"Pages"**
3. En "Source", selecciona **"Deploy from a branch"**
4. En "Branch", selecciona **"main"** y la carpeta **"/ (root)"**
5. Haz clic en **"Save"**

### Paso 5 — Tu sitio está en línea
En 2–3 minutos tu sitio estará disponible en:
```
https://TU_USUARIO.github.io/otero-ciberesculturas/
```

La página de Aurea estará en:
```
https://TU_USUARIO.github.io/otero-ciberesculturas/aurea.html
```

---

## Estructura de archivos

```
otero-ciberesculturas/
│
├── index.html              ← Página principal con las 13 obras
├── aurea.html              ← Página completa de Aurea (obra 01)
│
├── img/
│   └── aurea/
│       ├── aurea_slide.jpeg      ← Diapositiva original · escritura de Otero
│       ├── aurea_01.jpeg         ← Vista frontal · IBM 1987
│       ├── aurea_02.jpeg         ← Vista lateral · IBM 1987
│       ├── aurea_rec_01.jpeg     ← Reconstrucción · vista frontal
│       ├── aurea_rec_02.jpeg     ← Reconstrucción · vista aérea
│       ├── aurea_rec_03.jpeg     ← Reconstrucción · vista lateral
│       ├── aurea_ctx_01.jpeg     ← Contexto · Caracas nocturna
│       ├── aurea_ctx_02.jpeg     ← Contexto · frente al Ávila
│       └── aurea_ctx_03.jpeg     ← Contexto · escala humana
│
└── ar/
    └── Aurea_AR.usdz             ← Escultura en realidad aumentada (iPhone)
```

## Para agregar las siguientes obras

Por cada nueva escultura (ej: Satélite, obra 02):
1. Crea `satelite.html` (copia y adapta `aurea.html`)
2. Agrega las imágenes en `img/satelite/`
3. Agrega el archivo AR en `ar/Satelite_AR.usdz`
4. Actualiza el enlace en `index.html`
5. Sube los archivos nuevos al repositorio

---

## Cómo funciona el AR

- **iPhone (iOS Safari)**: al tocar el botón "Ver en realidad aumentada", el archivo `.usdz` abre automáticamente la cámara con la escultura en AR. No necesita ninguna app.
- **Android / otros dispositivos**: el botón descarga el archivo `.usdz`. Para AR nativo en Android se puede agregar también un archivo `.glb` en el futuro.

## Hashtags de la exposición

`#OteroCiberEscultura` · `#OteroEnMiMundo` · `#Otero2025` · `#ArteVenezolano`
