# Tarjeta digital — Katherine Guihur Berrocal · Grupo Indufrial

Misma base que las tarjetas de Adrián y Paola. Con LinkedIn, 5 catálogos,
logo repujado y descripción enfocada al canal institucional.

## ⚠️ DOS ARCHIVOS QUE DEBES SUBIR

No vienen en este paquete. Cópialos del repo de Paola (ya están corregidos allá):

| Archivo | De dónde sacarlo |
|---|---|
| `assets/img/logo-white.png` | Repo de Paola — es el logo con fondo transparente ya arreglado |
| `assets/img/avatar.jpg` | Foto de Katherine. Cuadrada, mínimo 400×400 px |

## Catálogos — nombres exactos

Súbelos a `assets/catalogos/`:

`refrigeracion.pdf` · `congelacion.pdf` · `importados.pdf` · `vending.pdf` ·
`maquinas-cafe.pdf` · `one-pager-corporativo.pdf`

## Pasos de publicación

1. Crear repo nuevo (ej. `vcard-katherine`), Public, sin README
2. Subir `index.html`, `style.css`, `README.md`
3. Crear carpetas con "Create new file":
   - `assets/img/.gitkeep`
   - `assets/catalogos/.gitkeep`
4. Subir `KatherineGuihur.vcf` en `assets/`
5. Subir logo y avatar en `assets/img/`
6. Subir los 6 PDFs en `assets/catalogos/`
7. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save

Recuerda: cada subida necesita el botón verde **"Commit changes"** al final.

## Logo

Ya viene en `height: 52px` y `opacity: 0.62` (el tamaño corregido).
Para ajustarlo, edita `.identity__logo` en `style.css`.
