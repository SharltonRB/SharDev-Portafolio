# SHAR.DEV — Página en construcción

Página estática (HTML + CSS, sin dependencias ni paso de compilación) que muestra el
**logotipo** y el **eslogan** "One endpoint at a time.", con aviso de sitio en construcción.
Es bilingüe (inglés principal, español de apoyo) y funciona en escritorio y celular.

```
index.html              Página completa
favicon.svg / .ico      Favicon (derivado del logo)
apple-touch-icon.png    Icono para iOS
assets/
  shardev-navbar-dark.svg   Logo para fondo oscuro
  fonts/                    Silkscreen y Space Grotesk (autoalojadas, licencia OFL)
```

## Publicar en Vercel

1. Sube esta carpeta a un repositorio (los archivos deben quedar en la raíz).
2. En vercel.com → **Add New… → Project** → importa el repositorio.
3. **Framework Preset: Other**. Deja vacíos Build Command y Output Directory.
4. **Deploy**. La URL queda como `https://<nombre-del-proyecto>.vercel.app`.

Alternativa sin repositorio: en esta carpeta, ejecutar `npx vercel` y seguir las preguntas.

## Publicar en GitHub Pages

1. Sube esta carpeta a un repositorio **público** (Pages gratis exige repo público).
2. **Settings → Pages → Build and deployment → Deploy from a branch** → `main` / `(root)`.
3. La URL queda como `https://<usuario>.github.io/<repositorio>/`.

## Antes de entregar

- Abre la URL en el navegador y confirma que se ven el logo, el eslogan y el favicon.
- Esa URL es la "Web del portafolio (homepage inicial)" que pide la tarea.
