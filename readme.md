# Tienda de GAMESTOP

Página web para la venta de videojuegos. 

## Funcionalidades

- **Navegación:** Utiliza la barra de navegación para moverte entre las diferentes secciones de la tienda.
- **Productos:** Encuentra los mejores videojuegos para todas las plataformas, incluyendo PlayStation, Xbox y Nintendo.

## Se Utilizó

- HTML
- CSS (utilizando la arquitectura SMACSS)

## Archivos SCSS

Este proyecto utiliza la arquitectura SMACSS (Scalable and Modular Architecture for CSS) para organizar los estilos CSS. Los archivos SCSS están estructurados de la siguiente manera:

- **`styles.scss`:** Este archivo principal importa todos los demás archivos SCSS y define variables globales.
- **`_base.scss`:** Contiene estilos básicos que afectan a elementos HTML de manera global, como fuentes y colores.
- **`_layout.scss`:** Define estilos relacionados con la disposición de los elementos en la página, como el encabezado, la navegación y el contenido principal.
- **`_navigation.scss`:** Contiene estilos específicos para la navegación, como efectos hover y modificadores para resaltar elementos activos.

## Modificadores

Los modificadores son clases CSS adicionales que se aplican a elementos HTML para cambiar su apariencia o comportamiento. En esta ocasion, hacemos uso de modificadores para la navegación:

- **`.navigation__item--active`:** Este modificador se aplica a elementos de navegación para resaltar el elemento activo. Se utiliza para indicar visualmente en qué sección de la tienda se encuentra.
- **Efectos Hover:** Se utilizan efectos hover para mejorar la experiencia al interactuar con los elementos de navegación y hacerlo mas atractivo. Cuando se pasa el cursor sobre un elemento, el color del texto se aclara ligeramente y un subrayado animado se muestra debajo del elemento.


