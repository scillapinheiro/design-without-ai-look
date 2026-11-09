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

Si no hay otros proyectos a la vista, pide una referencia o salta la comparación y avisa de que la saltaste.

Si la persona ya tiene colores, fuentes o logo de marca, esa es la identidad. Úsalos y construye el resto (composición, formas, tono) a su alrededor. La pregunta 3 pasa a ser: ¿qué colores y fuentes de la marca uso, y para qué función?

## Vicios que delatan el trabajo de IA (cada uno se puede liberar en el Paso 0)

**Píldoras de estado y etiquetas.** Etiquetas redondeadas como "NEW", "ON SALE", "LIVE", tags de categoría usadas como adorno. Alternativa: texto simple bien colocado, o un elemento del universo del concepto (sello, tampón, entrada, botón). Una etiqueta solo vale cuando lleva información que el visitante necesita en ese punto. Por qué: los generadores ponen una etiqueta de estado en cada bloque para parecer movimiento y novedad, y una etiqueta sin noticia nueva es solo ruido.

**Numeración.** Números de página, de sección o de tarjeta ("01", "02", "Page 2 of 5"), contadores decorativos y estadísticas sin fuente. Los datos reales necesarios (fechas, horarios, duraciones, precios) sí se pueden. Por qué: los números sugieren un proceso o un ranking que el contenido no tiene, y las estadísticas sin fuente parecen inventadas.

**Etiqueta minúscula en mayúsculas** sobre un titular grande, repetida en cada sección. Alternativa: un titular que se sostiene solo. Por qué: es un gesto hecho para crear jerarquía y, repetido en cada sección, se vuelve un sello de plantilla.

**Brillos y resplandores**, sombras de color difusas, degradados morado y azul genéricos. Alternativa: color plano con una función clara. Por qué: son el valor por defecto de los modelos de imagen y de los degradados prediseñados, así que dicen "generado" a primera vista.

**Cuadrícula de tres tarjetas iguales** con icono, título y frase. Alternativa: un layout hecho para el contenido. Por qué: llena una fila sin decidir qué importa, y la cuadrícula moldea el contenido en lugar de lo contrario.

**Iconos de línea genéricos** en lugar de arte pensado para el concepto. Por qué: vienen de los mismos pocos conjuntos de iconos que usa todo el mundo, así que no dicen nada de este concepto.

**Frases vagas de marketing** ("Elevate your sound", "Crafted with passion") y **lorem ipsum**. Escribe texto específico, con nombres, lugares y fechas verosímiles. Por qué: una frase que describiría cualquier producto no describe ninguno, y el texto provisional oculta si el layout funciona con palabras reales.

**Ilustrar donde la persona pondrá su propia foto.** La ilustración es arte de marca; los espacios de foto quedan vacíos y fáciles de cambiar. Por qué: la persona la va a cambiar de todos modos, y oculta que todavía falta una foto.

**La misma composición en todas las secciones** (título centrado, botón debajo, imagen de fondo). Alternativa: una idea visual por sección. Por qué: repetir un layout hace que la página parezca una sola idea estirada.

## Manías de la autora (activadas por defecto, libéralas con libertad)

Estas son más cuestión de gusto que señal de IA. Vienen activadas por defecto porque a la autora de esta skill no le gustan. Libera cualquiera en el Paso 0.

**Barras como separador.** Barra simple ("/") o doble ("//") entre palabras, en menús, etiquetas, fechas o créditos. Alternativa: un espacio, un punto medio, una línea o un elemento del concepto. Por qué: es un adorno en lugar de un separador, común en menús, fechas y créditos generados.

**Rayas en el texto.** Usa coma, punto o dos puntos. Por qué: las rayas largas son uno de los hábitos más reconocibles del texto generado.

**Serif cursiva** como "toque elegante" automático. Por qué: es una forma automática de parecer elegante que aparece en mucho trabajo generado.

## Hacer

- Cada sección tiene una idea visual propia ligada al concepto, no solo un bloque de texto sobre un fondo.
- Un elemento dominante por pantalla, con aire alrededor.
- Escala tipográfica con contraste real (titular mucho mayor que el cuerpo).
- Texto con voz de persona real: específico, corto, sin cliché.
- Contraste mínimo WCAG AA. Si hay un diseño o brief aprobado y falla, avisa a la persona y propón una corrección en lugar de cambiarlo por tu cuenta.
- Si ya existe un layout aprobado, respétalo: si el código o la revisión exigen cambiarlo, pregunta antes.

## Código

- HTML semántico, variables CSS al inicio para colores, fuentes y medidas.
- Al convertir un diseño existente en código, mantén la fidelidad a él: mismas secciones, orden, textos, colores y fuentes.
- Animación con propósito ligado al concepto, no un efecto de entrada genérico en todo.
- Ilustraciones y elementos de marca en SVG, no en imagen raster.

## Revisión final (antes de mostrar)

1. Revisa uno por uno los ajustes de la persona y la lista de vicios de arriba. Busca en especial píldoras olvidadas, números, barras y rayas en menús, pies de página, tarjetas y textos de apoyo.
2. Prueba del logo: si quitara el logo, ¿alguien sabría de qué proyecto es? Si no, falta identidad.
3. Prueba del vecino: ponlo junto a otro proyecto de la misma persona. Si cambiar el nombre y el color bastara para confundirlos, rehaz el esqueleto. Si no hay otro trabajo a la vista, pide una referencia o salta esta prueba y avisa de que la saltaste.
4. Informa de lo que encontraste y de lo que cambiaste.
