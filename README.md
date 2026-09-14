# Clariño

Web de **clarino.es**, alojada en GitHub Pages (rama `main`, raíz). Sitio estático de una sola página, sin build.

## Estructura

```
.
├── index.html            Página principal
├── 404.html              Página de error
├── CNAME                 Dominio personalizado (clarino.es)
├── robots.txt / sitemap.xml
└── assets/
    ├── styles.css
    ├── logo-clarino-white.svg / logo-clarino-oliva.svg
    ├── favicon.png / og-image.jpg
    ├── icons/            Iconografía de marca (oliva, blanco, cítrico) y lazo
    └── photos/
```

## Contenido y marca

- Textos basados en el plan de marketing de Clariño (propósito, Método Clariño, servicio, públicos, voz de marca).
- Identidad según el manual de marca: Montserrat (principal), MonteCarlo (destacados),
  paleta oliva `#61672A`, cítrico `#AD9F22`, avellana `#D0A583`, blanco cálido `#F7F5F0`, gris pedra `#4A4A4A`.

## Publicar cambios

Rama → PR → merge a `main`. GitHub Pages redespliega automáticamente en 1-2 minutos.

## Contacto

- Correo: `contacto@clarino.es`
- Teléfono / WhatsApp: `617 79 14 01`

No hay formulario: el contacto es directo (correo, WhatsApp y teléfono).

### DNS (Cloudflare)

- Registros `A` para el apex `clarino.es` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- Registro `CNAME` para `www` → `andresalonsomart.github.io`
