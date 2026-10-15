# InfoMates 🧉

Sitio web informativo sobre el mundo del mate y la yerba mate: estilos de mate, tipos de yerba y todo lo que hay que saber para cebar bien. Proyecto final del curso de Desarrollo Web de Coderhouse (Comisión 91305).

## 🔗 Sitio en vivo

**Deploy en Vercel:** [COMPLETAR CON LA URL DEL DEPLOY]

## 📄 Páginas

- **Inicio** — carousel de imágenes y presentación del sitio
- **Contacto** — formulario de contacto
- **Nosotros** — sobre el proyecto
- **Estilos de Yerba** — tipos de yerba mate (tradicional, uruguaya y barbacuá)
- **Estilos de Mate** — tipos de mate (camionero, imperial y torpedo)

## 🛠️ Tecnologías utilizadas

- HTML5 semántico
- SCSS con arquitectura de partials (utilities, base, layout, components)
- Bootstrap 5 (navbar responsive con menú hamburguesa, formularios, carousel)
- AOS (Animate On Scroll) para animaciones al hacer scroll
- Google Fonts (Poppins + Inter)
- Git / GitHub y despliegue en Vercel

## ✨ Características

- Diseño mobile-first, responsive en mobile, tablet y desktop
- SCSS con variables, nesting, mixins con parámetros (`respond`), `@extend` con placeholder y partials
- Animación nativa de entrada del logo con `@keyframes` y transiciones en el hover del navbar
- Animaciones al hacer scroll con AOS
- SEO on-page: `title` y meta `description`/`keywords` únicos por página, jerarquía de encabezados y `alt` descriptivo en las imágenes
- Contraste de colores revisado para accesibilidad

## 📁 Estructura del proyecto

```
├── index.html
├── pages/
│   ├── contacto.html
│   ├── nosotros.html
│   ├── estilos-de-yerba.html
│   └── estilos-de-mate.html
├── assets/
│   └── img/
├── styles/
│   └── styles.css          (compilado desde scss/)
└── scss/
    ├── main.scss            (solo imports con @use)
    ├── utilities/
    │   ├── _variables.scss
    │   └── _mixins.scss
    ├── base/
    │   ├── _base.scss
    │   └── _tipografia.scss
    ├── layout/
    │   ├── _header.scss
    │   ├── _nav.scss
    │   └── _footer.scss
    └── components/
        ├── _carousel.scss
        ├── _cards.scss
        ├── _buttons.scss
        └── _forms.scss
```

## 💻 Cómo correrlo localmente

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/lgasull91/entregafinal-comision91305.git
   cd entregafinal-comision91305
   ```

2. Instalá Sass (requiere [Node.js](https://nodejs.org/)):
   ```bash
   npm install -g sass
   ```

3. Compilá el SCSS (modo watch, recompila al guardar):
   ```bash
   sass --watch scss/main.scss:styles/styles.css
   ```

4. Abrí `index.html` en el navegador (recomendado: extensión **Live Server** de VS Code).

## 👤 Autor

Lautaro Gasull
