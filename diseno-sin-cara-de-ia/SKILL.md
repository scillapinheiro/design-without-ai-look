---
name: "diseno-sin-cara-de-ia"
description: "Úsala al diseñar o programar plantillas, sitios web y otros materiales gráficos (carteles, diapositivas, publicaciones, banners, portadas) para que el resultado tenga identidad propia en lugar del aspecto genérico de IA: decisiones escritas antes de diseñar, vicios por defecto personalizables, texto realista y una revisión final que se puede ejecutar."
---

# Diseño sin cara de IA

Usa esta skill siempre que diseñes cualquier material gráfico (sitio web o plantilla, cartel, diapositiva, publicación, banner, portada), lo construyas en una herramienta (Figma, Canva, etc.) o conviertas un diseño en código. El objetivo: dar a cada proyecto más posibilidades de tener una identidad propia, que no sea el valor por defecto de un generador.

## Paso 0: ajustes de la persona (valen más que cualquier regla de abajo)

La lista de vicios de esta skill es un punto de partida. La persona puede cambiarla de tres maneras:

1. **Añadir** cosas propias que evitar (un adorno que apareció demasiado, una forma, una costumbre de redacción).
2. **Liberar** vicios por defecto que no quiere quitar (por ejemplo, "se pueden usar píldoras" o "se pueden usar barras").
3. **Cambiar la alternativa** sugerida para un vicio, si prefiere otra.

Busca estos ajustes en CLAUDE.md, AGENTS.md o en el archivo de instrucciones que lee la herramienta, en el README, en el brief o en la conversación, en un bloque como este:

```
## Diseño sin cara de IA: ajustes
Añadir a evitar: ...
Liberar (no hace falta quitar): ...
Alternativas preferidas: ...
```

Si no hay ajustes, pregunta una sola vez, en el mismo mensaje que la pregunta de gusto del Paso 1, para que la persona reciba un mensaje y no dos: "¿Quieres añadir algo que no quieres ver, o liberar alguno de los vicios por defecto? ¿Y cómo te gusta que sea? Formas, colores, densidad, qué te parece bonito y qué te parece feo.". Si la persona responde solo una de las dos preguntas, usa la respuesta que llegó y valen los vicios por defecto para el resto. Anota los ajustes en el bloque de arriba y síguelos en todo el proyecto. Recuerda las reglas vigentes al empezar el trabajo.

## Paso 1: identidad antes del layout

Antes de elegir nada, necesitas el gusto de la persona en una frase. Se pide en el mensaje del Paso 0 de arriba; si los ajustes se encontraron en un archivo y el Paso 0 no preguntó nada, pregunta solo esto, por ejemplo: "¿Cómo te gusta que sea? Formas, colores, densidad, qué te parece bonito y qué te parece feo." Si tiene referencias, úsalas. Si no las tiene, esa frase basta. Diseña sin nada de esto solo si la persona dice que no tiene preferencia. Si un brief, una marca o respuestas anteriores ya muestran su gusto, úsalo y no vuelvas a preguntar. Por qué: en las pruebas, sin ningún gusto indicado el resultado caía en el promedio de lo que "parece buen diseño", y con una frase de gusto mejoraba mucho.

Antes de las cuatro respuestas de abajo, escribe tres direcciones, en una o dos líneas cada una. Si la persona no dio referencias, derívalas del contenido real del producto (sus objetos, lugar, clientes, lo que de verdad va a estar en la página) y haz que difieran en al menos tres de estos ejes: densidad, temperatura de color, voz de la tipografía, lenguaje de forma. Cada eje tiene que diferir por categoría y de forma perceptible (cálido o frío, escaso o denso, serif o sans redondeada, curva u ortogonal), y no por grado (un poco más cálido, un poco más denso). Revisa cada par de direcciones: si dos de los ejes que estás contando difieren poco, refuerza esos ejes o cambia la dirección. Una descripción distinta no basta, las decisiones en sí tienen que diferir. Cada dirección debe justificarse por el negocio, y no solo por ser distinta de las otras: distinta pero incoherente también falla. Elige una y di por qué; las cuatro respuestas de abajo valen para ella.

Después responde por escrito antes de diseñar, para la dirección que elegiste:
1. ¿Cuál es el universo real del concepto (objetos, materiales, lugares, época, sonidos)? Parte de lo que la persona tendría de verdad a mano, como el mostrador de un dueño o el piano de una profesora, y no de una metáfora de diseño.
2. ¿Cuál es el esqueleto (orden y forma de las secciones, o de los elementos en una pieza única)?
3. ¿Cuál es la paleta (3 a 5 colores, cada uno con una función) y la tipografía (elegida como dice el párrafo de tipografía de abajo)?
4. ¿Cuál es el elemento de marca? Algo hecho solo para este concepto, que no tendría sentido en otro.

Si la persona ya tiene colores, fuentes o logo de marca, esa es la identidad. Úsalos y construye el resto (composición, formas, tono) a su alrededor. La pregunta 3 pasa a ser: ¿qué colores y fuentes de la marca uso, y para qué función?

Ejemplo de las respuestas por escrito, para un cartel del concierto de otoño de un coro comunitario (todavía sin marca; el texto del ejemplo queda en inglés):

1. Universe: sheet music, breath, wooden church benches, October light.
2. Skeleton: one tall piece. The date and place come first and big, the program is a staggered list, the ticket line sits at the bottom. Not a centered title with a button.
3. Palette: ink brown for text, pumpkin for the date, cream for the paper, moss for small details. One serif for the choir's name (headlines) and one plain sans for the program and the ticket line (text and data).
4. Brand element: a row of singers drawn as simple shapes that grow from left to right like a rising scale. It would make no sense on any other piece.

Tipografía. Usa las familias que el concepto pida y justifica cada una por su función (títulos, texto, datos). Sigue este orden. Primero escribe qué tiene que hacer el texto pequeño (precios, fechas, leyendas, letra pequeña) y dónde se leerá, porque eso define qué tiene que aguantar la familia. Después propón tres candidatas (pares o familias únicas) ligadas al universo del concepto, como la mano de un rotulista, un libro de cuentas, un himnario, y di por qué encaja cada una. Elige una y di por qué. Al elegir la familia, comprueba que tenga ã, ç, é y ô completas, en los pesos que vas a usar. No empieces por los pares de reflejo dados como ejemplo en los vicios de abajo.

## Paso 2: decidir antes de diseñar

Escribe estas decisiones, con números reales, antes de diseñar. Son también la lista de comprobación de la revisión final.

| Decisión | Qué escribir |
|---|---|
| Elemento dominante | Aquello de lo que trata cada pantalla o página, y lo que le da espacio |
| Escala tipográfica | Tamaños reales de titular, subtítulo, cuerpo y texto pequeño (por ejemplo 72, 32, 18 y 14), con el titular varias veces mayor que el cuerpo |
| Unidad de espaciado | Una unidad base (por ejemplo 8) y los pocos múltiplos que vas a usar |
| Tres movimientos de composición | Tres decisiones que dan forma al layout, como un ancla descentrada, un recorte deliberado o un cambio de densidad entre secciones. No son adorno |

## Vicios que delatan el trabajo de IA (cada uno se puede liberar en el Paso 0)

El principio va antes de la lista: si tu primera idea serviría para cualquier negocio del mismo tipo, descártala y empieza de nuevo desde este negocio.

**Píldoras de estado y etiquetas.** Etiquetas redondeadas como "NEW", "ON SALE", "LIVE", tags de categoría usadas como adorno. Alternativa: texto simple bien colocado, o un elemento del universo real del concepto. No repitas la misma alternativa en secciones vecinas. Una etiqueta solo vale cuando lleva información que el visitante necesita en ese punto. Por qué: los generadores ponen una etiqueta de estado en cada bloque para parecer movimiento y novedad, y una etiqueta sin noticia nueva es solo ruido.

**Numeración.** Números de página, de sección o de tarjeta ("01", "02", "Page 2 of 5"), contadores decorativos y estadísticas sin fuente. Los datos reales necesarios (fechas, horarios, duraciones, precios) sí se pueden. Por qué: los números sugieren un proceso o un ranking que el contenido no tiene, y las estadísticas sin fuente parecen inventadas.

**Etiqueta minúscula en mayúsculas** sobre un titular grande, repetida en cada sección. Alternativa: un titular que se sostiene solo. Por qué: es un gesto hecho para crear jerarquía y, repetido en cada sección, se vuelve un sello de plantilla.

**Brillos y resplandores**, sombras de color difusas, degradados morado y azul genéricos. Alternativa: color plano con una función clara. Por qué: son el valor por defecto de los modelos de imagen y de los degradados prediseñados, así que dicen "generado" a primera vista.

**Cuadrícula de tres tarjetas iguales** con icono, título y frase. Alternativa: un layout hecho para el contenido. Por qué: llena una fila sin decidir qué importa, y la cuadrícula moldea el contenido en lugar de lo contrario.

**Iconos de línea genéricos** en lugar de arte pensado para el concepto. Por qué: vienen de los mismos pocos conjuntos de iconos que usa todo el mundo, así que no dicen nada de este concepto.

**Frases vagas de marketing** ("Elevate your sound", "Crafted with passion") y **lorem ipsum**. Escribe texto específico, con nombres, lugares y fechas verosímiles. Por qué: una frase que describiría cualquier producto no describe ninguno, y el texto provisional oculta si el layout funciona con palabras reales.

**Elegir el par de fuentes por reflejo.** El vicio es elegir el par sin pensar, y no el par en sí: ninguna fuente está prohibida. Alternativa: las candidatas que propusiste en el Paso 1, ligadas al concepto. Por qué: las fuentes que aparecen primero en el trabajo generado dicen "por defecto" antes de que alguien lea una palabra. Si el concepto justifica una de ellas por su función (títulos, texto, datos), úsala y di por qué. Ejemplos de pares a los que recurren los modelos (una suposición para que la autora la revise, y una lista que envejece como los ejemplos de abajo): Playfair Display con Inter o Lato, Fraunces con Inter, DM Serif Display con DM Sans, Cormorant Garamond con Montserrat, Space Grotesk para todo, Poppins o Montserrat solas para todo, Inter sola.

**Ilustrar donde la persona pondrá su propia foto.** La ilustración es arte de marca; los espacios de foto quedan vacíos y fáciles de cambiar. Por qué: la persona la va a cambiar de todos modos, y oculta que todavía falta una foto.

**La misma composición en todas las secciones** (título centrado, botón debajo, imagen de fondo). Alternativa: una idea visual por sección. Por qué: repetir un layout hace que la página parezca una sola idea estirada.

## Manías de la autora (activadas por defecto, libéralas con libertad)

Estas son más cuestión de gusto que señal de IA. Vienen activadas por defecto porque a la autora de esta skill no le gustan. Libera cualquiera en el Paso 0.

**Barras como separador.** Barra simple ("/") o doble ("//") entre palabras, en menús, etiquetas, fechas o créditos. Alternativa: un espacio, un punto medio, una línea o un elemento del concepto. Por qué: es un adorno en lugar de un separador, común en menús, fechas y créditos generados.

**Rayas en el texto.** Usa coma, punto o dos puntos. Por qué: las rayas largas son uno de los hábitos más reconocibles del texto generado.

**Serif cursiva** como "toque elegante" automático. Por qué: es una forma automática de parecer elegante que aparece en mucho trabajo generado.

## Ejemplos observados en pruebas (una lista abierta que envejece)

Vistos en noviembre de 2026 con Claude Sonnet 5.5, con el pedido "primera pantalla de una panadería de barrio". Los modelos cambian, así que lee esto como una muestra de valores por defecto, y no como una lista completa.

- Sin la skill: fondo crema con marrón y terracota, titular en serif con una palabra de otro color, hero en dos columnas con el objeto en un rectángulo redondeado a la derecha, una tarjeta o etiqueta flotante, un par de botones (uno relleno, uno con contorno), un pie en franja con tres columnas.
- Con una versión anterior de esta skill: el mismo objeto "entrada, sello o comanda" en todos los resultados (la lista de alternativas se volvió el siguiente vicio), líneas decorativas sueltas, una palabra recoloreada en el titular, un botón con sombra dura.
- Con una regla que decía "cambia paleta, tipografía y estructura a propósito": el extremo opuesto, un nombre gigante sobre un color plano saturado, una sola idea gritando. Un resultado tenía el titular cortado y otro una gran zona vacía, porque nadie renderizó el resultado.

## Hacer

- Cada sección tiene una idea visual propia ligada al concepto, no solo un bloque de texto sobre un fondo.
- Texto con voz de persona real: específico, corto, sin cliché.
- Contraste mínimo WCAG AA. Si hay un diseño o brief aprobado y falla, avisa a la persona y propón una corrección en lugar de cambiarlo por tu cuenta.
- Si ya existe un layout aprobado, respétalo: si el código o la revisión exigen cambiarlo, pregunta antes.

## Código

- HTML semántico, variables CSS al inicio para colores, fuentes y medidas.
- Al convertir un diseño existente en código, mantén la fidelidad a él: mismas secciones, orden, textos, colores y fuentes.
- Animación con propósito ligado al concepto, no un efecto de entrada genérico en todo.
- Ilustraciones y elementos de marca en SVG, no en imagen raster.

## Otros formatos

Todo lo anterior vale para cualquier formato: cartel, diapositiva, publicación, banner, portada y plantilla de sitio web. La identidad, el texto realista y la revisión final no cambian. Donde una regla se escribió para sitios web, así se lee en otros formatos:

| En un sitio web o plantilla | En otros formatos |
|---|---|
| Secciones y su orden | El orden y la agrupación de los elementos en la pieza: qué se lee primero, después y al final, o las diapositivas de una presentación en secuencia |
| Una idea visual por sección | Una idea visual por página, diapositiva o panel |
| Espacios de foto vacíos y fáciles de cambiar | Un marco vacío o caja provisional claramente marcada, con el tamaño que la foto necesita |
| HTML semántico, variables CSS al inicio | Estilos con nombre, capas y colores de tema, para cambiar un color o una fuente en un solo lugar |
| Arte de marca en SVG, no en imágenes raster | Arte de marca en formas vectoriales, no en imágenes aplanadas |
| Menús, pies de página y tarjetas | Encabezados, pies de página, leyendas, créditos y etiquetas |
| Animación con propósito | Movimiento solo donde el formato lo tiene (transiciones de diapositiva, vídeo, banner animado), con un propósito ligado al concepto |
| Fidelidad a un diseño existente | Si conviertes un diseño aprobado a otro formato o herramienta, mantén el mismo contenido, orden, colores y fuentes |

## Revisión final (antes de mostrar)

1. Revisa uno por uno los ajustes de la persona y la lista de vicios de arriba. Busca en especial píldoras olvidadas, números, barras y rayas en menús, pies de página, tarjetas y textos de apoyo.
2. Comprueba el resultado contra las decisiones de tu Paso 2: elemento dominante, escala tipográfica, unidad de espaciado, tres movimientos de composición.
3. Si puedes renderizar, renderiza en tamaño de escritorio y de móvil y ejecuta las seis primeras pruebas de abajo. Si no puedes, di que no comprobaste el resultado visual. La última prueba vale siempre.
4. Informa de lo que encontraste y de lo que cambiaste.

| Prueba | Qué buscar |
|---|---|
| Desenfoque | Desenfoca o entrecierra los ojos ante el render: ¿se sigue viendo la jerarquía? |
| Gris | Quita el color: ¿la página todavía se sostiene? |
| Cambio | Pon el texto de otro negocio: si nada en la página protesta, es genérica |
| Recuento | Tamaños de fuente, colores y componentes repetidos: ¿más de los que decidiste en el Paso 2? |
| Corte y vacío | Texto cortado por un borde, solapamientos, grandes zonas vacías |
| Cambio de fuente | Sustituye la fuente del titular por el par de reflejo más cercano al estilo elegido (por ejemplo, Poppins 800 para un titular redondeado y pesado): si la página queda igual o mejor, la elección de fuente no está trabajando para el concepto |
| Logo | Quita el logo: ¿alguien sabría de qué proyecto es? Si no, falta identidad |
