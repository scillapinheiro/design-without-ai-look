<h1 align="center">Diseño sin cara de IA</h1>

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.pt-BR.md">Português</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <a href="#computer-proyecto">Proyecto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-cómo-funciona">Cómo funciona</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sparkles-qué-evita">Qué evita</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#eyes-cómo-usarla">Cómo usarla</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licencia">Licencia</a>
</p>

<p align="center">
  <img alt="Licencia" src="https://img.shields.io/static/v1?label=licencia&message=MIT&color=6D4FD8&labelColor=grey">
  <img alt="Tipo" src="https://img.shields.io/static/v1?label=tipo&message=skill%20de%20Claude&color=137A67&labelColor=grey">
  <img alt="Idiomas" src="https://img.shields.io/static/v1?label=idiomas&message=EN%20%C2%B7%20PT%20%C2%B7%20ES&color=lightgrey&labelColor=grey">
</p>

## :computer: Proyecto

**Diseño sin cara de IA** es una skill para Claude que te ayuda a diseñar y programar plantillas y sitios web que no parecen hechos por una IA.

Nació de un problema real: mucha gente quiere hacer plantillas con IA, y los resultados comparten los mismos vicios. Píldoras de estado en todo, secciones numeradas, barras decorativas, tres tarjetas iguales en fila, un resplandor detrás del titular. Cada uno es pequeño, pero juntos delatan el trabajo.

La skill le da a Claude una lista por defecto de esos vicios que evitar, le pide que defina una identidad para cada proyecto antes de dibujar nada y termina con una revisión.

## :bulb: Cómo funciona

- **Tus ajustes van primero.** La lista por defecto es un punto de partida. Puedes añadir lo que no quieres ver, liberar vicios por defecto que sí te gustan y cambiar la alternativa sugerida para cualquiera.
- **Identidad antes del layout.** Antes de dibujar, Claude responde por escrito: cuál es el universo del concepto, cuál es el esqueleto, qué paleta y tipografía, y cuál es el elemento de marca que no tendría sentido en otro proyecto.
- **Una lista de vicios, cada uno con alternativa.** No solo "no hagas esto", sino qué hacer en su lugar.
- **Una revisión final.** Una prueba del logo (sin el logo, ¿alguien sabría de quién es el proyecto?) y una prueba del vecino (junto a otro proyecto tuyo, ¿es fácil confundirlos?).

## :sparkles: Qué evita

Estos son los valores por defecto. Todos se pueden liberar.

| Vicio | En su lugar |
|---|---|
| Píldoras de estado y etiquetas decorativas | Texto simple bien colocado, o un elemento del universo del concepto |
| Numeración de página, sección y tarjeta | Solo datos reales: fechas, horarios, duraciones, precios |
| Barras como separador | Un espacio, un punto medio, una línea |
| Rayas en el texto | Coma, punto o dos puntos |
| Etiqueta minúscula en mayúsculas sobre un titular grande | Un titular que se sostiene solo |
| Brillos, resplandores, degradados morado y azul genéricos | Color plano con una función clara |
| Tres tarjetas iguales con icono, título y frase | Un layout hecho para el contenido |
| Frases vagas de marketing y lorem ipsum | Texto específico, con nombres, lugares y fechas verosímiles |
| La misma composición en todas las secciones | Una idea visual por sección |

La lista completa, con los motivos, está en el archivo de la skill.

## :eyes: Cómo usarla

El repositorio tiene tres carpetas con la misma skill en tres idiomas.

| Idioma | Carpeta |
|---|---|
| English | `design-without-ai-look` |
| Português | `design-sem-cara-de-ia` |
| Español | `diseno-sin-cara-de-ia` |

**Instala solo una.** Si instalas más de una, Claude las carga todas a la vez.

### Claude (app y sitio web)

1. Descarga este repositorio (**Code, Download ZIP**) y descomprímelo.
2. Comprime en zip la carpeta del idioma que quieras. La carpeta debe tener el `SKILL.md` en el nivel superior.
3. En Configuración, abre el área de Skills y sube el zip. Los nombres de los menús cambian con el tiempo, así que revisa los actuales.

### Claude Code

Copia la carpeta del idioma a `~/.claude/skills/`, o a `.claude/skills/` dentro de un solo proyecto.

### Personalízala

Añade un bloque como este a tu `CLAUDE.md`, a tu brief, o simplemente díselo a Claude en la conversación:

    ## Diseño sin cara de IA: ajustes
    Añadir a evitar: notas adhesivas, tarjetas de estadísticas redondeadas
    Liberar (no hace falta quitar): píldoras de estado
    Alternativas preferidas: una línea simple en lugar de la barra entre elementos del menú

Si no hay ajustes, la skill pregunta una vez y anota tu respuesta en este bloque.

## :memo: Licencia

Publicada bajo la licencia MIT. Puedes usarla, copiarla, adaptarla y compartirla, siempre que mantengas el aviso de derechos de autor. Consulta el archivo [LICENSE](LICENSE).
