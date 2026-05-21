# EastBlue - Tienda de Natación

Prototipo de sitio web comercial desarrollado como proyecto integrador para la materia **Optimización de medios digitales para la Web: Imágenes gráficas** en la **Universidad de Guadalajara**.

## Demo en vivo

[Ver sitio demo](https://carlosrodriguezcab.github.io/PI-imagenes-para-sitio-web/)

## Objetivo académico

Editar un sitio web comercial optimizando las imágenes gráficas, tomando en cuenta la composición, el impacto visual y la coherencia con la identidad de marca.

## Descripción del proyecto

**EastBlue** es una tienda especializada en ropa y accesorios de natación. El sitio presenta una colección de productos orientada a nadadores de todos los niveles, desde entrenamiento recreativo hasta competencia de alto rendimiento.

### Páginas del sitio

| Archivo | Descripción |
|---|---|
| `index.html` | Página de inicio con hero, barra de confianza y catálogo destacado |
| `categoria-mujer.html` | Ejemplo de cómo se vería una página de categoría; muestra el catálogo de productos de mujer con enlaces al detalle |
| `pagina-de-producto.html` | Ejemplo de cómo se vería una página de producto; usa el Powerskin Carbon Core como caso de demostración |
| `nosotros.html` | Historia y valores de la marca |
| `contacto.html` | Formulario de contacto |

## Optimización de imágenes

El proyecto aplica las siguientes prácticas de optimización gráfica:

- **Formatos JPEG y PNG** para los recursos gráficos del sitio, siendo los formatos de compresión vistos en el curso: JPEG para fotografías de producto y recursos editoriales, PNG para elementos que requieren transparencia.
- **Formato WebP** para imágenes de producto (`producto-googles-1.webp`), reduciendo el peso respecto al JPEG original
- **Atributos `width` y `height`** en etiquetas `<img>` para evitar Layout Shift (CLS)
- **Texto alternativo descriptivo** en todas las imágenes para accesibilidad y SEO
- **Organización de assets** en carpetas separadas (`Productos/` y `Recursos/`) para facilitar el mantenimiento
- **Coherencia visual de marca** mediante paleta de color consistente (azul marino `#0c2d6e` + cian `#00aacf`) aplicada tanto en CSS como en las imágenes gráficas del banner y recursos

### Estructura de imágenes

```
Imagenes/
├── Productos/          # Fotografías de productos
│   ├── producto-googles-1.jpg
│   ├── producto-gorra-azul.jpg
│   ├── producto-gorra-rosa.jpg
│   ├── producto-toalla.jpg
│   └── producto-traje-negro.jpg (+ variantes)
└── Recursos/           # Imágenes editoriales, banners y logo
    ├── logo.png
    ├── banner-verano.png
    └── (fotografías ambientales de natación)
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Font Awesome 6 (iconografía)

## Paleta de color

| Token | Valor | Uso |
|---|---|---|
| `--primary` | `#0c2d6e` | Encabezados, navbar |
| `--accent` | `#00aacf` | Botones CTA, detalles |
| `--bg` | `#f5f8ff` | Fondo general |
| `--surface` | `#ffffff` | Tarjetas y contenedores |

## Estructura del proyecto

```
Prototipo/
├── index.html
├── categoria-mujer.html
├── pagina-de-producto.html
├── nosotros.html
├── contacto.html
├── estilos.css
└── Imagenes/
    ├── Productos/
    └── Recursos/
```

## Datos académicos

- **Materia:** Optimización de medios digitales para la Web: Imágenes gráficas
- **Universidad:** Universidad de Guadalajara (UDG)
- **Semestre:** Segundo semestre
- **Autor:** Carlos Rodríguez Caballero
