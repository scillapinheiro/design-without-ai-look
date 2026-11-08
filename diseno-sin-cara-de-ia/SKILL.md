---
name: "diseno-sin-cara-de-ia"
description: "Úsala al diseñar o programar plantillas y sitios web para evitar el aspecto genérico de IA: identidad propia, vicios por defecto personalizables, texto realista y una revisión final."
---

# Diseño sin cara de IA

Usa esta skill siempre que diseñes un layout, lo construyas en una herramienta (Figma, Canva, etc.) o conviertas un diseño en código. El objetivo: cada proyecto tiene identidad propia, no parece salido de un generador y no se parece a otro proyecto de la misma persona.

## Paso 0: ajustes de la persona (valen más que cualquier regla de abajo)

La lista de vicios de esta skill es un punto de partida. La persona puede cambiarla de tres maneras:

1. **Añadir** cosas propias que evitar (un adorno que apareció demasiado, una forma, una costumbre de redacción).
2. **Liberar** vicios por defecto que no quiere quitar (por ejemplo, "se pueden usar píldoras" o "se pueden usar barras").
3. **Cambiar la alternativa** sugerida para un vicio, si prefiere otra.

Busca estos ajustes en CLAUDE.md, README, el brief o la conversación, en un bloque como este:

```
## Diseño sin cara de IA: ajustes
Añadir a evitar: ...
Liberar (no hace falta quitar): ...
Alternativas preferidas: ...
```

Si no hay ajustes, pregunta una sola vez, en una frase: "¿Quieres añadir algo que no quieres ver, o liberar alguno de los vicios por defecto?". Anota la respuesta en el bloque de arriba y síguela en todo el proyecto. Recuerda las reglas vigentes al empezar el trabajo.

## Paso 1: identidad antes del layout

Responde por escrito antes de diseñar:
1. ¿Cuál es el universo del concepto (objetos, materiales, lugares, época, sonidos)?
2. ¿Cuál es el esqueleto (orden y forma de las secciones)? ¿Es distinto de los proyectos ya hechos?
3. ¿Cuál es la paleta (3 a 5 colores, cada uno con una función) y la tipografía (máximo 2 familias)? ¿Ninguna repite la de otro proyecto?
4. ¿Cuál es el elemento de marca? Algo hecho solo para este concepto, que no tendría sentido en otro.

Si el esqueleto, la paleta o la tipografía se parecen a los de otro proyecto, cámbialos antes de seguir.

## Vicios por defecto que evitar (cada uno se puede liberar en el Paso 0)

**Píldoras de estado y etiquetas.** Etiquetas redondeadas como "NEW", "ON SALE", "LIVE", tags de categoría usadas como adorno. Alternativa: texto simple bien colocado, o un elemento del universo del concepto (sello, tampón, entrada, botón). Una etiqueta solo vale cuando lleva información que el visitante necesita en ese punto.

**Numeración.** Números de página, de sección o de tarjeta ("01", "02", "Page 2 of 5"), contadores decorativos y estadísticas sin fuente. Los datos reales necesarios (fechas, horarios, duraciones, precios) sí se pueden.

**Barras como separador.** Barra simple ("/") o doble ("//") entre palabras, en menús, etiquetas, fechas o créditos. Alternativa: un espacio, un punto medio, una línea o un elemento del concepto.

**Rayas en el texto.** Usa coma, punto o dos puntos.

**Etiqueta minúscula en mayúsculas** sobre un titular grande, repetida en cada sección.

**Serif cursiva** como "toque elegante" automático.

**Brillos y resplandores**, sombras de color difusas, degradados morado y azul genéricos.

**Cuadrícula de tres tarjetas iguales** con icono, título y frase.

**Iconos de línea genéricos** en lugar de arte pensado para el concepto.

**Frases vagas de marketing** ("Elevate your sound", "Crafted with passion") y **lorem ipsum**. Escribe texto específico, con nombres, lugares y fechas verosímiles.

**Ilustrar donde la persona pondrá su propia foto.** La ilustración es arte de marca; los espacios de foto quedan vacíos y fáciles de cambiar.

**La misma composición en todas las secciones** (título centrado, botón debajo, imagen de fondo).

## Hacer

- Cada sección tiene una idea visual propia ligada al concepto, no solo un bloque de texto sobre un fondo.
- Un elemento dominante por pantalla, con aire alrededor.
- Escala tipográfica con contraste real (titular mucho mayor que el cuerpo).
- Texto con voz de persona real: específico, corto, sin cliché.
- Contraste mínimo WCAG AA. Si el diseño falla, avisa a la persona en lugar de corregirlo por tu cuenta.
- Respetar lo ya aprobado: si el código o la revisión exigen cambiar un layout aprobado, pregunta antes.

## Código

- HTML semántico, variables CSS al inicio para colores, fuentes y medidas.
- Fidelidad al diseño: mismas secciones, orden, textos, colores y fuentes.
- Animación con propósito ligado al concepto, no un efecto de entrada genérico en todo.
- Ilustraciones y elementos de marca en SVG, no en imagen raster.

## Revisión final (antes de mostrar)

1. Revisa uno por uno los ajustes de la persona y la lista de vicios de arriba. Busca en especial píldoras olvidadas, números, barras y rayas en menús, pies de página, tarjetas y textos de apoyo.
2. Prueba del logo: si quitara el logo, ¿alguien sabría de qué proyecto es? Si no, falta identidad.
3. Prueba del vecino: ponlo junto a otro proyecto de la misma persona. Si cambiar el nombre y el color bastara para confundirlos, rehaz el esqueleto.
4. Informa de lo que encontraste y de lo que cambiaste.
