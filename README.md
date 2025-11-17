# Parte 4: Introducción a CSS

## Objetivo
Explicar qué es CSS, cómo funciona su sintaxis y mostrar ejemplos prácticos aplicados a una página web sencilla.

---

## Teoría

### ¿Qué es CSS?
CSS significa **Cascading Style Sheets** (Hojas de Estilo en Cascada).  
Su función principal es separar el contenido (HTML) del diseño (CSS).

Con CSS se puede:
- Cambiar colores, tamaños y fuentes.
- Definir márgenes y espacios.
- Adaptar el diseño a distintos dispositivos (PC, tablet, móvil).
- Crear animaciones y transiciones.

Ejemplo cotidiano: Facebook se ve distinto en celular, tablet y computadora, gracias a CSS.

---

### Anatomía de CSS
Un bloque de CSS se compone de:

1. **Selector**: indica qué elemento HTML se va a modificar (`p`, `h1`, `.clase`, `#id`).
2. **Llaves `{ }`**: delimitan el bloque de estilos.
3. **Propiedades**: características que queremos cambiar (`color`, `font-size`, `margin`).
4. **Valores**: el resultado que asignamos a la propiedad (`blue`, `20px`, `center`).

Ejemplo:

```css
p {
  color: blue;
  font-size: 18px;
}
```
