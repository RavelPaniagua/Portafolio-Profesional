# Portafolio profesional

Sitio estático personal construido con HTML, CSS y Tailwind CSS v4. El archivo compilado `tailwind.css` se publica junto a la página para que GitHub Pages no dependa de un proceso de build en el servidor.

## Desarrollo

```bash
npm install
npm run dev:css
```

Abre `index.html` en el navegador. Antes de publicar cambios, genera el CSS optimizado:

```bash
npm run build
```

Incluye `tailwind.css` en el commit para que GitHub Pages publique los estilos actualizados.