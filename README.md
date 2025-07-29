# Prueba Técnica Tecalis

Este repositorio contiene la prueba técnica para el puesto de **Maquetadora Web** en Tecalis. El objetivo es demostrar una maquetación **pixel perfect** y **responsive**, siguiendo los diseños proporcionados en Figma.

---

## 📋 Índice

1. [Descripción](#descripción)
2. [Demo](#demo)
3. [Instalación](#instalación)
4. [Estructura de archivos](#estructura-de-archivos)
5. [Tecnologías](#tecnologías)
6. [Características](#características)
7. [Detalles de implementación](#detalles-de-implementación)
8. [Variables CSS](#variables-css)
9. [Autor](#autor)

---

## 📝 Descripción

Maquetación de una página acorde a los diseños entregados en Figma, con dos versiones:

* **Móvil**: hasta 430 px de ancho, basado en colapsables (accordions).
* **Escritorio**: desde 1024 px, display en dos columnas y sistema de pestañas (tabs).

Se ha respetado cada medida, color y espacio para lograr un resultado pixel perfect.

---

## 💾 Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/ZoeRuiz/prueba-maquetacion.git
   ```
2. Entra en la carpeta del proyecto:

   ```bash
   cd prueba-maquetacion
   ```
3. Abre `index.html` directamente en tu navegador o usa un servidor local:

   ```bash
   npx http-server .
   ```

---

## 📂 Estructura de archivos

```
prueba-maquetacion/
├── img/                     # Imágenes y assets
├── css/
│   └── styles.css           # Estilos (mobile-first + desktop)
├── index.html               # Archivo HTML principal
└── README.md                # Documentación
```

---

## 🛠 Tecnologías

* **HTML5**
* **CSS3**: Variables, Grid, Flexbox, Mobile-First
* **JavaScript**: Handlers mínimos para toggles y tabs
* **Google Fonts**: Montserrat
* **Git & GitHub**: Control de versiones

---

## ✨ Características

* **Responsive**: Adaptación fluida de móvil a escritorio.
* **Pixel Perfect**: Implementación exacta de los diseños.
* **Accordions móviles**: Collapse funcional con íconos dinámicos.
* **Tabs de escritorio**: Cambio de contenido lateral.
* **Variables CSS**: Tipografías y medidas centralizadas.

---

## 🔍 Detalles de implementación

* **Mobile (≤430px)**: `.collapse` con `aria-expanded` y `hidden` para accesibilidad.
* **Desktop (≥1024px)**: `@media` queries con grids de 720×400 px y alturas fijadas.
* **Decorativo**: Elemento `.decor-top-right` posicionado en esquina.

---

## 🎨 Variables CSS

En `:root` se definen:

```css
--ff-heading, --ff-body
--fs-h1…--fs-body-2
--lh-h1…--lh-body-2
```

Para ajustar tipografía y espaciados globales.

---

## 👤 Autor

**Zoraida Ruiz** — Maquetadora Web

* GitHub: [ZoeRuiz](https://github.com/ZoeRuiz)
* Email: [zoraida.ruiz89@gmail.com](mailto:zoraida.ruiz89@gmail.com)

*¡Gracias por revisar mi trabajo!*
