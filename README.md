# PetShop - Tienda de Productos para Animales

Sitio web moderno y responsive para una tienda de productos para mascotas.

## Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica, ARIA, microdatos |
| CSS3 | Variables CSS, animaciones, responsive design |
| Bootstrap 5.3 | Grid, componentes, utilities |
| Bootstrap Icons | Iconografía |
| Google Fonts (Poppins) | Tipografía |
| JavaScript vanilla | Lógica del carrito, filtros, búsqueda, validaciones |
| localStorage | Persistencia del carrito entre sesiones |
| IntersectionObserver | Animaciones al hacer scroll |

## Estructura del Proyecto

```
tiendaAniamles/
├── index.html              # Página principal (semántica, accesible)
├── README.md               # Documentación del proyecto
├── .gitignore              # Exclusiones para Git
└── assets/
    ├── css/
    │   └── style.css       # Estilos con variables CSS y media queries
    └── js/
        └── script.js       # JS modular con estado centralizado
```

## Buenas prácticas implementadas

### HTML
- Etiquetas semánticas (`<header>`, `<main>`, `<nav>`, `<section>`)
- Atributos ARIA (`aria-label`, `aria-current`, `aria-live`, `aria-hidden`)
- Meta tags optimizados (description, theme-color, robots)
- Preconexiones (preconnect) para mejorar tiempo de carga
- Lazy loading en imágenes (`loading="lazy"`)
- Favicon inline (SVG data URI)

### CSS
- Variables CSS (`:root`) para theming centralizado
- Nomenclatura consistente de clases
- Organización por secciones con comentarios
- Media queries con breakpoints Bootstrap estándar
- Transiciones y animaciones optimizadas (GPU)

### JavaScript
- Estado centralizado en objeto `state`
- Funciones puras y separadas por dominio
- Manejo de errores en localStorage
- Event delegation donde aplica
- Código comentado por módulos

## Imágenes

Todas las imágenes provienen de [Unsplash](https://unsplash.com/) con URLs verificadas funcionales. Cada producto tiene imagen principal y fallback.

## Funcionalidades

- **Catálogo**: 10 productos con nombre, descripción, precio, imagen y categoría
- **Productos destacados**: Sección independiente con marcador `featured`
- **Carrito**: Agregar, eliminar, actualizar cantidad, subtotal, vaciar. Persiste en localStorage
- **Búsqueda**: Filtrado en tiempo real por nombre, descripción o categoría
- **Filtros**: Por categoría (Perros, Gatos, Aves, Peces) y desde cards de categorías
- **Formulario**: Validación HTML5 con feedback visual Bootstrap
- **FAQ**: Acordeón Bootstrap con 4 preguntas frecuentes
- **Notificaciones**: Toast dinámicos con反馈 visual
- **Scroll animations**: IntersectionObserver para animaciones de entrada
- **WhatsApp flotante**: Botón con enlace directo
- **Volver arriba**: Botón con scroll suave

## Cómo usar

1. Abre `index.html` en tu navegador.
2. No requiere servidor ni dependencias adicionales.

## Licencia

Uso libre y gratuito.
