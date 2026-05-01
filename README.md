# Portfolio QA - Manuel Macias

Portafolio profesional para GitHub Pages enfocado en QA Testing, APIs, pagos, WHMCS, e-commerce, SQL y documentación técnica.

## Estructura

```bash
portfolio-qa-manuel/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── favicon.svg
│   └── cv-manuel-macias.pdf
└── README.md
```

## Cómo editarlo

### 1. Cambiar datos de contacto

En `index.html`, busca esta sección:

```html
<a class="btn primary" href="mailto:tu-correo@example.com">Enviar email</a>
<a class="btn secondary" href="https://www.linkedin.com/in/tu-linkedin/">LinkedIn</a>
<a class="btn secondary" href="https://github.com/tu-usuario">GitHub</a>
```

Reemplaza:

- `tu-correo@example.com`
- `https://www.linkedin.com/in/tu-linkedin/`
- `https://github.com/tu-usuario`

### 2. Agregar tu CV

Reemplaza el archivo:

```bash
assets/cv-manuel-macias.pdf
```

por tu CV real con el mismo nombre.

### 3. Personalizar proyectos

Edita las tarjetas dentro de la sección:

```html
<section id="proyectos">
```

Cada tarjeta usa esta estructura:

```html
<article class="project-card">
  ...
</article>
```

### 4. Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube estos archivos.
3. Ve a `Settings > Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Selecciona la rama `main` y carpeta `/root`.
6. Guarda los cambios.

La URL quedará similar a:

```text
https://tu-usuario.github.io/
```

Si el repositorio se llama exactamente `tu-usuario.github.io`, GitHub lo publicará como sitio principal.
