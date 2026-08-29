# 🍰 Recetas de Postres

Página web de recetas de postres, construida con HTML, CSS y JavaScript puro.

## 📁 Estructura del proyecto

```
recetas-postres/
├── index.html              # Página principal (listado/portada de recetas)
├── README.md                # Este archivo
│
├── css/
│   ├── styles.css           # Estilos generales (reset, variables, layout)
│   ├── components.css       # Estilos de componentes reutilizables (cards, navbar, footer...)
│   └── responsive.css       # Media queries / adaptación a móvil y tablet
│
├── js/
│   ├── main.js               # Lógica principal (inicialización, eventos)
│   ├── recetas.js            # Datos y/o lógica de las recetas (array/objeto con recetas)
│   └── utils.js               # Funciones auxiliares reutilizables
│
├── img/
│   ├── postres/               # Fotos de cada postre
│   └── iconos/                 # Iconos (SVG/PNG) usados en la UI
│
├── recetas/
│   ├── tarta-chocolate.html   # Página individual de receta (una por postre)
│   ├── flan-casero.html
│   └── ...
│
└── assets/
    └── fonts/                  # Tipografías locales, si no usas Google Fonts
```

## 🧩 Convenciones sugeridas

- **Nombres de archivo:** (`TartaChocolate.html`) no en minúsculas y con guiones (`tarta-chocolate.html`).
- **Una carpeta `recetas/`** con una página HTML por receta, en vez de meterlo todo en `index.html`, para que crezca ordenado.
- **CSS dividido por responsabilidad** (`styles`, `components`, `responsive`) en vez de un único archivo gigante.
- **`recetas.js`** puede empezar como un array de objetos JS con los datos de cada receta (nombre, ingredientes, pasos, imagen, tiempo de preparación) — así luego es fácil migrar a JSON o a un backend si el proyecto crece.

## ✅ Próximos pasos típicos

- [ ] Maquetar `index.html` con el listado de postres (cards)
- [ ] Crear la plantilla base de una página de receta individual
- [ ] Definir la estructura de datos de una receta en `recetas.js`
- [ ] Añadir estilos responsive
- [ ] (Opcional) Filtro/buscador de recetas con JS

---

_Estructura pensada para HTML/CSS/JS puro. Si en el futuro migras a Vue o React, la carpeta `recetas/` pasaría a ser componentes/rutas dinámicas en lugar de páginas HTML sueltas._
