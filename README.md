# Stely — Landing Page

Landing page estática de Stely para publicar en GitHub Pages.

**URL final:** `https://lisan1313.github.io/stely-landing/`

---

## Archivos incluidos

```
landing/
├── index.html      → Página principal (hero + funciones + CTA + footer)
├── privacy.html    → Política de Privacidad (stub — rellenar con Iubenda)
├── terms.html      → Términos de Uso (stub — rellenar con Iubenda)
├── style.css       → Estilos. Paleta Stely: #0F0E14 · #E8B547 · #F5EDD8
├── assets/         → Carpeta para logo, imágenes futuras
└── README.md       → Este archivo
```

---

## Pasos para publicar en GitHub Pages

### 1. Crear el repositorio en GitHub

1. Ve a **github.com** e inicia sesión con tu cuenta (`Lisan1313`).
2. Pulsa el botón verde **"New"** (arriba a la izquierda).
3. Nombre del repositorio: `stely-landing`
4. Visibilidad: **Public** (necesario para GitHub Pages gratis).
5. No marques ninguna opción extra (sin README, sin .gitignore).
6. Pulsa **"Create repository"**.

### 2. Subir los archivos

**Opción A — Desde el navegador (más fácil):**

1. En la página del repo recién creado, pulsa **"uploading an existing file"**.
2. Arrastra TODOS los archivos de esta carpeta `landing/` al área de subida:
   - `index.html`
   - `privacy.html`
   - `terms.html`
   - `style.css`
3. En el campo "Commit changes" escribe: `feat: landing inicial Stely`
4. Pulsa **"Commit changes"**.

**Opción B — Con GitHub Desktop:**

1. Clona el repo `stely-landing` en tu ordenador.
2. Copia todos los archivos de `landing/` al interior de la carpeta clonada.
3. En GitHub Desktop verás los archivos como cambios pendientes.
4. Escribe un mensaje de commit: `feat: landing inicial Stely`
5. Pulsa **"Commit to main"** → luego **"Push origin"**.

### 3. Activar GitHub Pages

1. En tu repositorio `stely-landing`, ve a **Settings** (pestaña superior).
2. En el menú lateral izquierdo, busca **"Pages"**.
3. En "Branch", selecciona **`main`**.
4. En "Folder", selecciona **`/ (root)`**.
5. Pulsa **"Save"**.
6. Espera 1-2 minutos.
7. Aparecerá el mensaje: *"Your site is live at https://lisan1313.github.io/stely-landing/"*

### 4. Usar la URL en Iubenda

Una vez que la landing esté publicada, usa esta URL en Iubenda:

```
https://lisan1313.github.io/stely-landing/
```

Iubenda generará tu Política de Privacidad y Términos de Uso con esa URL como dominio.

### 5. Integrar los textos legales de Iubenda

Cuando Iubenda te genere los textos:

1. Abre `privacy.html` y sustituye el bloque `<div class="legal-placeholder">` con el HTML que da Iubenda.
2. Haz lo mismo en `terms.html`.
3. Sube los archivos actualizados (repite el paso 2).
4. Los cambios se publican en 1-2 minutos.

---

## Pendientes para completar la landing

- [ ] Email de contacto definitivo en footer (actualmente `hola@stely.app` — cambiar si es diferente)
- [ ] Logo/icono real de Stely en la carpeta `assets/` cuando Sandra lo tenga
- [ ] Textos legales de Iubenda en `privacy.html` y `terms.html`
- [ ] Links reales de Google Play / App Store cuando la app esté publicada
- [ ] Actualizar año en footer si procede

---

## Paleta y diseño

| Elemento | Color |
|---|---|
| Fondo | `#0F0E14` negro nocturno cinematográfico |
| Dorado | `#E8B547` acento principal |
| Texto | `#F5EDD8` cream cálido |

Sin frameworks. HTML + CSS puro. Zero JavaScript. Carga instantánea.
