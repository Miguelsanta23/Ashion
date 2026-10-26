# Ashion - Tienda de moda

Maquetación de la página de inicio de **Ashion** para Programacion 4.

- **Autor:** Miguel Angel Santafe Castrillon
- **Tecnologías:** HTML5, CSS3, Bootstrap 5.3 (grillas), Bootstrap Icons, Google Fonts
- **Metodología CSS:** BEM

## Demo
https://ashion-miguelsantafe.netlify.app


## Estructura del proyecto

```
Ashion/
├── index.html        → estructura de la página
├── css/
│   └── styles.css    → estilos propios con BEM
├── img/              → imagenes (logo es texto con la fuente Cookie)
└── README.md
```

## Cómo se usa Bootstrap

| Clase | Para qué sirve |
|-------|----------------|
| `navbar navbar-expand-lg` | Menu que se vuelve hamburguesa en pantallas < 992px |
| `container-fluid` | Contenedor que ocupa todo el ancho |
| `row g-2` | Fila de la grilla con separación pequeña entre columnas |
| `col-12 col-lg-6` | 100% en celular/tablet, 50% en PC |
| `col-12 col-md-6` | 100% en celular, 50% desde tablet |

## Cómo se usa BEM

BEM = **Bloque__Elemento--Modificador**

| Bloque | Elementos | Modificadores |
|--------|-----------|---------------|
| `header` | `header__logo`, `header__link`, `header__icons`, `header__badge` | `header__link--active` |
| `hero` | `hero__content`, `hero__title`, `hero__text`, `hero__button`, `hero__image` | — |
| `category` | `category__content`, `category__title`, `category__count`, `category__button`, `category__image` | `category--men`, `category--kids`, `category--cosmetics`, `category--accessories` |

## Responsive

- **PC (≥ 992px):** tarjeta grande a la izquierda y 4 tarjetas en cuadrícula 2x2 a la derecha.
- **Tablet (768px - 991px):** tarjeta grande arriba y debajo las 4 tarjetas en 2 columnas.
- **Celular (< 768px):** todas las tarjetas una debajo de otra y menú hamburguesa.
