Proyecto de práctica evaluable: **Currículum Vitae Web** hecho con **HTML5 semántico** y **CSS**

### Tecnologías usadas
- HTML5 (semántica: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- CSS3 (variables, Flexbox, Grid, `@media print`, pseudo-elementos)

### Estructura del proyecto (obligatoria)

```
.
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── favicon.svg
│── png/
│   └── yo.jpeg
│   └── github-logo-png_seeklogo-304612.png
└── README.md
```

### Qué incluye (resumen)
- Diseño **mobile-first** y **responsive** (breakpoint: `min-width: 768px`).
- Accesibilidad básica: `alt` en imágenes, enlaces descriptivos y **focus visible** al navegar con Tab.
- 1 animación CSS con sentido (hover en navegación).
- 1 pseudo-elemento con propósito real (`.timeline::before`).
- Modo impresión con `@media print` y **URLs visibles** (con `content: attr(href)`).

### Cómo probarlo
1. Abre `index.html` en el navegador.
2. Responsive: abre DevTools y cambia a vista móvil / escritorio.
3. Impresión: `Ctrl+P` → vista previa (deberías ver las URLs de los enlaces).

### Deploy en Vercel (pasos sencillos)
1. Sube el proyecto a GitHub (repo público o privado).
2. Entra en Vercel y crea un “New Project” importando el repo.
3. Vercel lo detecta como **sitio estático** (no hace falta build).
4. Deploy y copia la URL final.

**URL del deploy:** `vercel-4f4ormkji-jiahaochenxus-projects.vercel.app`