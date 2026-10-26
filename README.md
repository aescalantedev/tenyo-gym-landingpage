# Tenyo Web Landing Page & Legal Portal

Landing page oficial y portal de políticas de privacidad para la aplicación **Tenyo: Rutinas de Gym y Casa**, diseñada con [Astro](https://astro.build), [Tailwind CSS v4](https://tailwindcss.com) e iconos vectoriales de [@lucide/astro](https://lucide.dev).

## 🚀 Rutas Principales
- `/`: Landing page de alta conversión (Hero, beneficios, mapa Rive, capturas, FAQ, Buy Me a Coffee).
- `/privacy`: **Política de Privacidad oficial** lista para ingresar en Google Play Console.

## 📦 Comandos Disponibles

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev

# Compilar para producción (SSG estático en /dist)
pnpm build

# Vista previa de la compilación
pnpm preview
```

## 🌐 Despliegue en subdominio (tenyo.aescalante.dev)

### En Vercel o Cloudflare Pages:
1. Conecta este repositorio o carpeta a tu proyecto.
2. Build command: `pnpm build`
3. Output directory: `dist`
4. En la configuración de dominio, añade el dominio personalizado `tenyo.aescalante.dev`.
5. Apunta el registro CNAME en tu DNS hacia tu proveedor.
