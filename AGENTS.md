# AGENTS.md

## Proyecto
Landing page estático para el **Club Aeroespacial de la escuela**, con enfoque en su CanSat y la cronología del Mundial de CanSats.

## Stack y convenciones
- **Stack**: HTML5, CSS3 y JavaScript vanilla (sin frameworks ni bundlers).
- **Entrada**: Servir `index.html` directamente (servidor local simple como *Live Server* o `python -m http.server`).
- **Idioma**: Español (es-419).

## Activos clave
| Archivo | Ubicación | Nota |
|---|---|---|
| Logo del club | `assets/logo.svg` | Mantén este SVG como logo principal en la navegación y el footer. |
| Imagen de inspiración | `inspo.png` | **Referencia de diseño principal** para el estilo visual del sitio (oscuro, minimalista, tipografía *bold* con temática espacial). |
| Prompts de IA | `assets/image-prompts.md` | Contiene prompts listos para generar imágenes complementarias con ChatGPT Image u otro modelo. |

## Estructura y estética esperada
- **Estilo visual**: Fiel a `inspo.png`. Paleta oscura, tipografía grande enfatizada, espacios amplios, imágenes espaciales cinematográficas y un diseño limpio/moderno.
- **Secciones mínimas (landing page)**:
  1. *Hero*: Visual impactante con foto de espacio y call-to-action claro.
  2. *Descripción del club*: "Qué hacemos".
  3. *CanSat*: Información sobre el proyecto y diseño (CAD).
  4. *Cronología*: Historia/timeline del Mundial de CanSats.
  5. *Galería/contacto*: Fotos del grupo e info de contacto.

## Formato de carpetas sugerido
```
/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── logo.svg
│   ├── image-prompts.md
│   └── images/   <-- guarda aquí fotos del grupo y el CanSat
└── inspo.png     <-- solo referencia
```

## Notas operativas
- Antes de subir a producción o generar nuevas imágenes, consulta **`assets/image-prompts.md`**.
- El logo es un SVG; asegúrate de que los colores se vean bien sobre fondos oscuros (puede requerir una versión de color blanco o un filtro de color CSS).
