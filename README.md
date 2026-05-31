# ⬛ Portafolio Personal — Jesús Emiliano López Espinoza

<div align="center">

![Minecraft Style](https://img.shields.io/badge/Estilo-Minecraft-5D9C3A?style=for-the-badge&logo=creativecommons&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Sin dependencias](https://img.shields.io/badge/Dependencias-Ninguna-17CE5E?style=for-the-badge)

**Portafolio web personal con temática Minecraft, construido con HTML, CSS y JavaScript puro.**  
Sin frameworks, sin librerías externas, sin npm. Solo un archivo `index.html`.

[🌐 Ver en vivo](#) · [📄 Mi CV](#) · [✉️ Contacto](mailto:emiliano.espinoza118@gmail.com)

</div>

---

## 📋 Contenido

- [Vista previa](#-vista-previa)
- [Características](#-características)
- [Tecnologías](#-tecnologías)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Cómo ejecutar localmente](#-cómo-ejecutar-localmente)
- [Cómo publicar en GitHub Pages](#-cómo-publicar-en-github-pages)
- [Conceptos utilizados](#-conceptos-utilizados)
- [Autor](#-autor)

---

## 🖼 Vista previa

> Portafolio con temática pixelada de Minecraft: paleta de colores de tierra, diamante, esmeralda y oro. Animaciones CSS, efecto de tipeo, barras de XP y bloques en 3D.

---

## ✨ Características

- 🎮 **Diseño 100% Minecraft** — colores, bloques 3D, fuente pixelada `Press Start 2P`
- ⚡ **Sin dependencias** — solo HTML + CSS + JS vanilla, un único archivo
- 📱 **Responsivo** — adaptado para móvil, tablet y escritorio con CSS Grid y `clamp()`
- 🌀 **Animaciones CSS puras** — bloques flotantes, cursor parpadeante, partículas cayendo
- 🔭 **Scroll animations** — elementos aparecen al hacer scroll con `IntersectionObserver`
- ⌨️ **Efecto de tipeo** — subtítulo animado que escribe y borra texto en bucle
- 📊 **Barras de XP** — habilidades visualizadas como barras de experiencia de Minecraft
- 🚀 **Listo para producción** — se puede subir directamente a GitHub Pages, Netlify o Vercel

---

## 🛠 Tecnologías

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura semántica de la página |
| **CSS3** | Estilos, variables, animaciones, grid, responsive |
| **JavaScript (ES6)** | IntersectionObserver, efecto tipeo, partículas |
| **Google Fonts** | Fuentes `Press Start 2P` y `VT323` (pixeladas) |

> ⚠️ Las fuentes se cargan desde Google Fonts. Se requiere conexión a internet para verlas correctamente.

---

## 📁 Estructura del proyecto

```
portafolio-minecraft/
│
└── index.html        ← Todo el proyecto en un solo archivo
                         (HTML + CSS embebido + JS embebido)
```

El proyecto es intencionalmente un **single file** para máxima portabilidad. Si crece, se puede separar en:

```
portafolio-minecraft/
│
├── index.html
├── css/
│   └── styles.css
└── js/
    └── main.js
```

---

## 🚀 Cómo ejecutar localmente

### Opción 1 — Live Server (recomendada para desarrollo)

1. Instala [Visual Studio Code](https://code.visualstudio.com/)
2. Instala la extensión **Live Server** de Ritwick Dey (`Ctrl+Shift+X` → buscar "Live Server")
3. Abre `index.html` en VS Code
4. Haz clic en **"Go Live"** en la barra inferior derecha
5. Se abrirá en `http://127.0.0.1:5500` con recarga automática al guardar

### Opción 2 — Abrir directamente en el navegador

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/portafolio-minecraft.git

# Entra a la carpeta
cd portafolio-minecraft

# Abre el archivo en tu navegador
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

---

## 🌐 Cómo publicar en GitHub Pages

1. Sube el repositorio a GitHub
2. Ve a **Settings** → **Pages**
3. En "Branch", selecciona `main` y carpeta `/ (root)`
4. Haz clic en **Save**
5. En unos minutos tu portafolio estará en:  
   `https://tu-usuario.github.io/portafolio-minecraft/`

> También funciona con **Netlify** y **Vercel** con drag & drop del archivo `index.html`.

---

## 📚 Conceptos utilizados

Para quien quiera aprender del código, estos son los conceptos clave empleados:

| Concepto | Descripción |
|---|---|
| `CSS Custom Properties` | Variables globales de color en `:root { }` |
| `CSS Grid` | Layouts responsivos sin frameworks |
| `clamp()` | Tipografía fluida que escala con el viewport |
| `@keyframes` | Animaciones: flotar, parpadear, caer, latido |
| `IntersectionObserver` | Detectar cuándo un elemento entra en pantalla |
| `position: fixed` | Navegación que no se mueve al hacer scroll |
| `data-*` attributes | Almacenar el % de llenado en las barras de XP |
| `scrollIntoView` | Scroll suave al hacer clic en los links de la nav |
| `setInterval` | Generar partículas cayendo cada 600ms |

---

## 👤 Autor

**Jesús Emiliano López Espinoza**  
Ingeniero en Sistemas Computacionales — TecNM La Piedad

- 📧 [emiliano.espinoza118@gmail.com](mailto:emiliano.espinoza118@gmail.com)
- 📍 La Piedad, Michoacán, México
- 📱 352 132 1113

---

<div align="center">

Hecho con ❤️ y mucho Java  
© 2026 Jesús Emiliano López Espinoza

</div>
