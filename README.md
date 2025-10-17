# Landing Page iPhone 15

Proyecto personal de landing page moderna y responsiva sobre iPhone 15, desarrollada con Astro y Tailwind CSS. Incluye animaciones GSAP, carrusel de logos, secciones de features con iconos SVG, comentarios de clientes y footer con redes sociales.

## 🚀 Tecnologías principales
- [Astro](https://astro.build/) (framework principal)
- [Tailwind CSS](https://tailwindcss.com/) (estilos utilitarios)
- [GSAP](https://gsap.com/) (animaciones)
- SVGs nativos para iconos y logos

## 📦 Estructura del proyecto

```
/
├── public/           # Imágenes y SVGs públicos
├── src/
│   ├── assets/       # Imágenes webp del iPhone 15
│   ├── components/   # Navbar y Footer
│   ├── layouts/      # Layout global con SEO
│   ├── pages/        # index.astro (landing principal)
│   └── styles/       # global.css (Tailwind)
├── package.json      # Dependencias y scripts
├── astro.config.mjs  # Configuración Astro
├── tailwind.js       # Configuración Tailwind
└── README.md         # Este archivo
```

## 🧑‍💻 Instalación y uso

1. **Instala dependencias:**
   ```sh
   pnpm install
   # o
   npm install
   ```

2. **Inicia el servidor de desarrollo:**
   ```sh
   pnpm dev
   # o
   npm run dev
   ```
   Accede a `http://localhost:4321` en tu navegador.

3. **Compila para producción:**
   ```sh
   pnpm build
   # o
   npm run build
   ```

4. **Previsualiza el build:**
   ```sh
   pnpm preview
   # o
   npm run preview
   ```

## 🛠️ Dependencias principales
- `astro`
- `tailwindcss`
- `gsap`
- `@astrojs/tailwind`

## 📄 Notas para desarrolladores
- Los SVGs de logos están en `/public/`
- Las imágenes del iPhone 15 están en `src/assets/`
- Los componentes principales son `Navbar.astro` y `Footer.astro`
- El layout global y SEO está en `src/layouts/Layout.astro`
- El archivo principal de la landing es `src/pages/index.astro`
- Las animaciones GSAP están en el script de `index.astro`

## 📬 Contacto
Para dudas o sugerencias, abre un issue o contacta al autor.

---

**Autor:** Santilook
**Fecha:** Octubre 2025
