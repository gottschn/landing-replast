# RePlast landing

Landing estática basada en el mockup visual provisto. No requiere instalación ni proceso de build.

## Publicar en Cloudflare Pages

- Framework preset: `None`
- Build command: dejar vacío
- Build output directory: `dist`

También se puede subir la carpeta `dist` directamente con Direct Upload.

## Vista local

Desde la raíz del proyecto:

```powershell
python -m http.server 4173 --directory dist
```

Antes de publicar, reemplazá el enlace genérico de WhatsApp en `dist/index.html` por el número real usando el formato `https://wa.me/549...`.
