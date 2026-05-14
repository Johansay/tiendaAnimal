# PetShop - Tienda de Productos para Animales

Sitio web moderno y responsive para una tienda de productos para mascotas, construido con **HTML5**, **CSS3**, **Bootstrap 5** y **JavaScript vanilla**.

## Características

- Navbar responsive con contador dinámico del carrito
- Hero section con overlay y animaciones
- Catálogo de 10 productos con imágenes reales (Pexels / Unsplash)
- Categorías: Perros, Gatos, Aves, Peces
- Buscador en tiempo real y filtros por categoría
- Carrito de compras funcional con persistencia en localStorage
- Formulario de registro con validaciones HTML5
- Sección FAQ con accordion Bootstrap
- Testimonios de clientes
- Diseño responsive (mobile, tablet, desktop)
- Efectos hover, animaciones y transiciones CSS
- Botón flotante de WhatsApp y botón "Volver arriba"

## Estructura del Proyecto

```
tiendaAniamles/
├── index.html              # Página principal
├── README.md               # Documentación
├── .gitignore              # Archivos ignorados por Git
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos personalizados
│   └── js/
│       └── script.js       # Lógica JavaScript (carrito, filtros, etc.)
```

## Tecnologías utilizadas

| Tecnología | Propósito |
|---|---|
| HTML5 | Estructura semántica del sitio |
| CSS3 | Estilos, animaciones y diseño responsive |
| Bootstrap 5.3 | Grid system, componentes (navbar, cards, modal, accordion, form) |
| Bootstrap Icons | Íconos de redes sociales y UI |
| Google Fonts (Poppins) | Tipografía moderna |
| JavaScript vanilla | Carrito de compras, búsqueda, filtros, validaciones |
| localStorage | Persistencia del carrito entre sesiones |

## Imágenes

Todas las imágenes son obtenidas de:
- [Pexels](https://www.pexels.com/) — imágenes principales
- [Unsplash](https://unsplash.com/) — imágenes de respaldo (fallback)

## Cómo usar

1. Clona o descarga el repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. No requiere servidor ni dependencias adicionales — funciona directamente.

## Funcionalidades JavaScript

- **Catálogo**: Array de objetos con 10 productos (nombre, descripción, precio, imagen, categoría, descuento).
- **Carrito**: Agregar, eliminar, actualizar cantidad, calcular subtotal y vaciar. Persiste en localStorage.
- **Búsqueda**: Filtrado en tiempo real por nombre, descripción o categoría.
- **Filtros**: Botones para filtrar productos por categoría de mascota.
- **Productos destacados**: Sección separada con los productos marcados como `featured`.
- **Scroll animations**: Animaciones al hacer scroll usando IntersectionObserver.
- **Toast notifications**: Notificaciones visuales al agregar/quitar productos del carrito.

## Licencia

Este proyecto es de uso libre y gratuito.
