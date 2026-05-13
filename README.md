# Exercise - HTML5 & CSS3 - Frontend - Reproduce using Flexbox

## Descripción
Ejercicio de maquetación con HTML5 y CSS3 reproduciendo un diseño dado utilizando Flexbox. El diseño es responsive y se adapta a escritorio y móvil.

## Tecnologías utilizadas
- HTML5
- CSS3
  - Flexbox
  - Variables CSS (Custom Properties)
  - @import para modularización
  - @font-face para fuente local
- Fuente Inter (descargada desde Google Fonts y servida en local)

## Estructura del proyecto
├── css/
│   ├── style.css      → importa los módulos CSS
│   ├── base.css       → variables, reset, fuentes y estilos generales
│   └── card.css       → estilos de las cards
├── fonts/
│   └── Inter-VariableFont.ttf  → fuente Inter en local
├── imgs/
│   ├── html5.svg               → logo HTML5
│   ├── css3.svg                → logo CSS3
│   ├── 01-desktop-version.png  → diseño de referencia escritorio
│   └── 01-mobil-version.png    → diseño de referencia móvil
└── index.html                  → estructura HTML principal

## Ramas utilizadas
- `main` → rama principal, versión final entregable
- `dev` → rama de desarrollo, donde se integran todas las features
- `feature/html-structure` → estructura HTML base con las dos cards
- `feature/flexbox-layout` → estilos CSS con Flexbox y módulos
- `feature/responsive` → media queries para diseño móvil
- `feature/typography` → fuente local con @font-face y estilos tipográficos

## Flujo de trabajo Git
1. Fork del repositorio del profe
2. Clone del fork en local
3. Creación de rama `dev` desde `main`
4. Para cada feature:
   - `git checkout -b feature/nombre` desde `dev`
   - Trabajo en VSCode
   - `git add .`
   - `git commit -m "mensaje descriptivo"`
   - `git push origin feature/nombre`
   - `git checkout dev`
   - `git merge feature/nombre`
   - `git push origin dev`
5. Pull Request de `dev` → `main`

## Commits realizados
- `Add HTML structure` → estructura HTML base con las dos cards
- `Fix index.html location to root` → corrección de ubicación del archivo
- `Add flexbox layout, CSS modules and update README` → CSS modularizado con variables y Flexbox
- `Add responsive design for mobile` → media queries para móvil
- `Remove accidental dev file` → limpieza de archivo accidental
- `Add local typography with @font-face and update README` → fuente Inter en local

## Requisitos cumplidos
- [x] Flexbox para el layout
- [x] Google Fonts (Inter) — descargada y servida en local con @font-face
- [x] Enlace "Learn more about HTML" → https://lenguajehtml.com/html/
- [x] Enlace "Learn more about CSS" → https://lenguajecss.com/css/
- [x] Diseño responsive para móvil y escritorio
- [x] Desplegado en GitHub Pages

## Enlaces
- Repositorio: https://github.com/AndreaVaGo/ex-html-css-frontend-reproduce-using-flexbox
- GitHub Pages: (pendiente)