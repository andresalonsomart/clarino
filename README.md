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

- Textos según el documento de la clienta `Pagina web 1.7.docx` (inicio, qué es Clariño,
  Método Clariño, servicios, "puede que Clariño sea para ti si…", confianza, sobre mí y contacto).
  El plan de marketing sigue siendo la referencia de tono y de mensajes.
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
