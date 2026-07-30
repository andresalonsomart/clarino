# Clarino

Web de **clarino.es**, alojada en GitHub Pages.

## Estructura

```
.
├── index.html        Página principal
├── 404.html          Página de error
├── CNAME             Dominio personalizado (clarino.es)
├── robots.txt        Indexación
├── sitemap.xml       Mapa del sitio
└── assets/
    ├── styles.css
    ├── logo.svg
    └── favicon.svg
```

## Publicar cambios

Cada push a `main` redespliega la web automáticamente:

```bash
git add . && git commit -m "descripción" && git push
```

## Dominio

El sitio se sirve en `https://clarino.es`. La configuración DNS necesaria
(registros A al apex + CNAME para www) está documentada más abajo.

### DNS

- Registros `A` para el apex `clarino.es` → IPs de GitHub Pages:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Registro `CNAME` para `www` → `andresalonsomart.github.io`
