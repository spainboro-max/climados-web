# Clima.Dos — Sitio web estático

Web de una página para **Clima.Dos**, empresa de venta, instalación, reparación y mantenimiento de aire acondicionado en Mallorca.

- **Stack:** HTML único (`index.html`) + Tailwind CSS por CDN + JS vanilla inline. Sin build.
- **Fuente:** Inter (Google Fonts).
- **SEO:** metadatos completos, Open Graph y JSON-LD `LocalBusiness`/`HVACBusiness`.
- **Producción prevista:** https://www.climados.com

## Estructura

```
index.html
assets/
  cli-1.png       # Hero
  cli-2.png       # Sección "Nosotros"
  cli-3.png       # Logotipo completo
  logo-icon.png   # Icono recortado (navbar / favicon)
```

## Desarrollo local

Cualquier servidor estático sirve, por ejemplo:

```bash
python -m http.server 8642
```
