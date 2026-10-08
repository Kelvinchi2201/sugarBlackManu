# Sugar Black - Menú Virtual

Un catálogo frontend de postres rápido y optimizado, diseñado con temática oscura y toques dorados[cite: 18].

🔗 **Sitio en vivo:** [https://sugar-black-manu.vercel.app/](https://sugar-black-manu.vercel.app/)

## 🚀 Tecnologías
*   **Framework:** Astro
*   **Estilos:** Tailwind CSS

## 📂 Estructura Principal
*   `src/pages/index.astro`: Renderiza la cuadrícula principal y el listado completo de los postres[cite: 16].
*   `src/components/DessertItem.astro`: Componente de la tarjeta individual con estilos, control de dimensiones de imagen y efectos hover[cite: 17].
*   `src/layouts/Layout.astro`: Plantilla HTML base que gestiona los metadatos de la página y el fondo global del sitio[cite: 18].

## 💻 Desarrollo Local

Ejecuta los siguientes comandos en tu terminal para trabajar en el proyecto:

```bash
# Instalar todas las dependencias necesarias
npm install

# Iniciar el servidor de desarrollo (por defecto en http://localhost:4321)
npm run dev

# Generar el proyecto para producción (si no usas el auto-deploy de Vercel)
npm run build
