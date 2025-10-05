# Culturama

Sitio estático moderno para descubrir eventos culturales — maqueta para practicar maquetación y UI.

---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-blue?style=for-the-badge)](https://dany1986-dra.github.io/Culturama/)

<!-- Badges de tecnologías -->

:rocket: Tecnologías principales:

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-typography-blue?style=for-the-badge&logo=google) ![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-lightgrey?style=for-the-badge&logo=javascript)

## Descripción

Culturama es una página web estática pensada como maqueta para listar y descubrir eventos culturales. Contiene una cabecera con búsqueda, banners, categorías destacadas, una sección de próximos eventos y una agenda con notificaciones simuladas.

El objetivo del repositorio es practicar maquetación con HTML y CSS, trabajar layouts con Grid y Flexbox, y adaptar estilos modernos (botones, sombras y gradientes) para una apariencia profesional.

## Vista previa

> Capturas (se usan imágenes existentes en `assets/img/` como ejemplo)

### Capturas (ejemplo)

![Banner principal](assets/img/banner1.png)

![Evento de ejemplo](assets/img/evento-1.png)

![Agenda (ejemplo)](assets/img/agenda-1.png)

## Tecnologías

Esta maqueta está construida con tecnologías web puras. Los "botones" de tecnologías abajo usan shields (imagenes) para verse como badges visuales.

![HTML5](https://img.shields.io/badge/-HTML5-orange?style=for-the-badge&logo=html5) ![CSS3](https://img.shields.io/badge/-CSS3-blue?style=for-the-badge&logo=css3) ![CSS Grid](https://img.shields.io/badge/-CSS%20Grid-%237F8FFE?style=for-the-badge) ![Flexbox](https://img.shields.io/badge/-Flexbox-%2356B78C?style=for-the-badge) ![Google Fonts](https://img.shields.io/badge/-Google%20Fonts-4285F4?style=for-the-badge&logo=google) ![Meyer Reset](https://img.shields.io/badge/-Meyer%20Reset-%23D9D9D9?style=for-the-badge)

## Estructura del proyecto

```text
Culturama/
├─ index.html        # Página principal
├─ README.md         # Este archivo
└─ assets/
  ├─ img/           # Imágenes: banners, eventos, iconos
  └─ style/         # CSS: style.css, grid.css, flex.css
```

## Cómo ejecutar (sin Python)

Opciones sencillas y compatibles sin Python:

1. Abrir directamente: haz doble clic en `index.html` y ábrelo en el navegador.

2. Usar la extensión Live Server (VS Code): instala "Live Server" y pulsa "Go Live".

3. Usar npx (Node.js): si tienes Node instalado, desde la carpeta del proyecto:

```powershell
npx live-server --port=8000
# o
npx serve -s . -l 8000
```

Luego abre [http://localhost:8000](http://localhost:8000).

## Estética y paleta de colores

Se aplicó una paleta vibrante y profesional en `assets/style/style.css`. Colores principales:

- Primario (azul oscuro): #0B2B4A
- Acento naranja: #F66139
- Acento rosa: #FF6B9A
- Amarillo destacado: #FFC756

Los componentes principales usan gradientes, sombras suaves y bordes redondeados para una apariencia moderna y accesible.

## Botones y componentes (guía rápida)

- `.btn` — clase base para botones.
- `.btn--primary` — botón principal con gradiente naranja→rosa.
- `.btn--secondary` — botón secundario con borde.
- `.card` — tarjeta con sombra para eventos y preview.

Ejemplo en HTML:

```html
<button class="btn btn--primary">Ver</button>
<button class="btn btn--secondary">Notifícame</button>
<div class="card"> ... </div>
```

Si quieres, puedo aplicar estas clases en `index.html` automáticamente.

## Buenas prácticas y próximas mejoras

- Añadir meta tags completos para SEO y Open Graph.
- Mejorar accesibilidad (roles ARIA, foco keyboard-friendly).
- Optimizar imágenes y servir versiones responsivas (srcset).
- Añadir un workflow de CI/CD para desplegar a GitHub Pages.

## Contribuir

Si quieres colaborar, crea un fork del repositorio, haz tus cambios y abre un pull request. Incluye una pequeña descripción de las mejoras y capturas si afectan la UI.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` en la raíz del repositorio para el texto completo.

### Publicar demo en GitHub Pages

1. Asegúrate de que el repositorio está en GitHub y la rama principal es `main`.
2. Haz push de tus cambios:

```powershell
git add .
git commit -m "Actualización: estilos, README y workflow de GH Pages"
git push origin main
```

3. El workflow `.github/workflows/gh-pages.yml` que añadí publicará la raíz del repo en la rama `gh-pages`. Espera algunos minutos después del push.
4. La URL del demo será `https://<TU_USUARIO>.github.io/<TU_REPO>/`. Sustituye `<TU_USUARIO>` y `<TU_REPO>` en el README o dámelos y lo actualizo.

## Contacto

Desarrollado por Daniel Rivera Alpízar.

¿Quieres que aplique las clases de botón y tarjeta directamente en el HTML ahora? También puedo agregar capturas al README y badges adicionales (por ejemplo: demo en GH Pages).

