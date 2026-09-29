
# Jesús de la Garsa - Web
React + Vite + Tailwind + Framer Motion

## Deploy a Vercel

### Opción rápida (Vercel CLI)
1. npm i -g vercel
2. vercel login
3. Dentro de esta carpeta: vercel --prod

### Opción GitHub
1. Crea repo en GitHub y haz push de esta carpeta
2. Entra a vercel.com > Add New Project > Import Git Repository
3. Framework: Vite, Build Command: npm run build, Output: dist
4. Deploy

## Notas
- Edita src/App.tsx
- SHOW_IMAGE_IDS = false para ocultar IDs en producción
- siteData.email editable en App.tsx
- Imágenes en src/assets/
