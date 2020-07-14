## Formas de reutilizar estilos

La curva de aprendizaje de CSS es baja: rápidamente podemos ponernos en acción y lograr cambios positivos en nuestros formularios. Pero cuando se trata de buscar técnicas de reutilización, nos encontramos con dificultades, aun cuando se trata de un lenguaje declarativo y que tiene reglas sencillas que están pensadas para aplicarse "en cascada":

- el estilo de fuente que definimos se aplica desde el elemento raíz hacia los hijos
- también hemos visto que definir un font-size de 10 píxeles permite trabajar con medidas espaciales relativas `em` y `rem` en cascada
- si tenemos este tag html

```html
<div class="saraza">
  Soy un div
</div>
```

hemos visto en [el ejemplo de especificidad](https://github.com/uqbar-project/css-01-especificidad) que podemos trabajar con reglas generales para los divs y más específicas para las clases:

```css
div {
  /* reglas a aplicar para los divs */
}

.saraza {
  /* reglas específicas para tags que tengan clase saraza */
}
```

De todas maneras, después de estar acostumbrados a trabajar en el paradigma OO, css está lejos de tener técnicas similares para la reutilización de código.

## Técnica BEM: Block, Element, Modifier

## Material adicional

- [BEM 101](https://css-tricks.com/bem-101/)
- [Building a Scalable CSS Architecture with BEM and Utility Classes](https://css-tricks.com/building-a-scalable-css-architecture-with-bem-and-utility-classes/)
- [Get BEM](http://getbem.com/)