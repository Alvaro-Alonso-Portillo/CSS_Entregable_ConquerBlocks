# 📌 Proyecto CSS Entregable

## 📖 Descripción

Este proyecto es una maquetación web utilizando **HTML, SASS (SCSS) y CSS**. Se enfoca en un diseño moderno y responsivo con efectos interactivos en el `header`, botones y navegación.

## 🚀 Características

- Uso de **SASS** para una mejor organización del código CSS.
- Header con navegación interactiva.
- Botones con efectos `hover` dinámicos.
- Diseño responsivo adaptable a diferentes dispositivos.
- Código estructurado y optimizado con @import en SASS.

## 📂 Estructura del Proyecto

```bash
CSS_Entregable/
│── css/                 # Archivos CSS compilados
│── img/                 # Imágenes y recursos
│── sass/                # Archivos fuente SASS
│   ├── abstracts/       # Variables y mixins
│   ├── base/            # Estilos base (reset, tipografías)
│   ├── components/      # Componentes reutilizables (botones, cards, etc.)
│   ├── layout/          # Estructura general (header, footer, etc.)
│   ├── pages/           # Estilos específicos por página
│   ├── themes/          # Temas de colores
│   ├── vendors/         # Librerías externas
│   ├── style.scss       # Archivo principal que importa todo
│── src/                 # Archivos JavaScript
│   ├── main.js          # Archivo principal de scripts
│── .gitignore           # Archivos y carpetas a ignorar en Git
│── index.html           # Archivo principal HTML
│── README.md            # Documentación del proyecto
│── package.json         # Dependencias del proyecto
│── vite.config.js       # Configuración de Vite (si aplica)
```

## 🛠️ Instalación y Uso

1. **Clonar el repositorio:**
   ```sh
   git clone https://github.com/Alvaro-Alonso-Portillo/CSS_Entregable_ConquerBlocks.git
   cd CSS_Entregable_ConquerBlocks
   ```
2. **Instalar dependencias (si usas SASS con Node.js):**
   ```sh
   npm install
   ```
3. **Compilar los archivos SASS:**
   ```sh
   npx sass sass/style.scss css/style.css --watch
   ```
4. **Abrir ************`index.html`************ en el navegador.**

## 📌 Tecnologías Utilizadas

- **HTML5**
- **SASS (SCSS)**
- **CSS3**
- **JavaScript (opcional, si hay interactividad)**

## ✨ Mejoras Futuras

- Implementar un `modo oscuro`.
- Añadir animaciones con `@keyframes`.
- Optimizar los estilos CSS reduciendo redundancias.
- Integrar más componentes reutilizables en SASS.

##

---

¡Gracias por revisar este proyecto! 🎨🔥

Creado con ❤️ por [Alvaro Alonso Portillo]