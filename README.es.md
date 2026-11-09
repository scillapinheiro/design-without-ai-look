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
  <img alt="Tipo" src="https://img.shields.io/static/v1?label=tipo&message=SKILL.md&color=137A67&labelColor=grey">
  <img alt="Idiomas" src="https://img.shields.io/static/v1?label=idiomas&message=EN%20%C2%B7%20PT%20%C2%B7%20ES&color=lightgrey&labelColor=grey">
  <img alt="Versión" src="https://img.shields.io/static/v1?label=versi%C3%B3n&message=1.0.0&color=lightgrey&labelColor=grey">
</p>

## :computer: Proyecto

**Diseño sin cara de IA** es una skill que ayuda a una IA a diseñar y programar plantillas, sitios web y otros materiales gráficos (carteles, diapositivas, publicaciones, banners, portadas) que no parecen hechos por una IA. Se hizo con Claude y funciona como skill de Claude; mira "Otras herramientas de IA" más abajo para el resto.

Nació de un problema real: mucha gente quiere hacer plantillas con IA, y los resultados comparten los mismos vicios. Píldoras de estado en todo, secciones numeradas, barras decorativas, tres tarjetas iguales en fila, un resplandor detrás del titular. Cada uno es pequeño, pero juntos delatan el trabajo.

La skill le da a la IA una lista por defecto de esos vicios que evitar, le pide que defina una identidad para cada proyecto antes de dibujar nada y termina con una revisión.

## :bulb: Cómo funciona

- **Tus ajustes van primero.** La lista por defecto es un punto de partida. Puedes añadir lo que no quieres ver, liberar vicios por defecto que sí te gustan y cambiar la alternativa sugerida para cualquiera.
- **Identidad antes del layout.** Antes de dibujar, la IA responde por escrito: cuál es el universo del concepto, cuál es el esqueleto, qué paleta y tipografía, y cuál es el elemento de marca que no tendría sentido en otro proyecto.
- **Una lista de vicios, cada uno con alternativa.** No solo "no hagas esto", sino qué hacer en su lugar.
- **Cualquier material gráfico.** Carteles, diapositivas, publicaciones, banners, portadas y plantillas de sitio web. Una tabla en la skill dice cómo se lee cada regla de sitio web en los otros formatos.
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

Las barras, las rayas y la serif cursiva son manías de la autora: vienen activadas por defecto y son fáciles de liberar. La lista completa, con los motivos, está en el archivo de la skill.

## :eyes: Cómo usarla

El repositorio tiene tres carpetas con la misma skill en tres idiomas.

| Idioma | Carpeta |
|---|---|
| English | `design-without-ai-look` |
| Português | `design-sem-cara-de-ia` |
| Español | `diseno-sin-cara-de-ia` |

**Instala solo una.** Si instalas más de una, Claude las carga todas a la vez.

### Claude (app y sitio web)

1. Descarga el zip de tu idioma desde la página de Releases: `design-without-ai-look-v1.0.0.zip` (English), `design-sem-cara-de-ia-v1.0.0.zip` (Português) o `diseno-sin-cara-de-ia-v1.0.0.zip` (Español). O descarga este repositorio (**Code, Download ZIP**), descomprímelo y comprime en zip la carpeta del idioma que quieras. La carpeta debe tener el `SKILL.md` en el nivel superior.
2. En Configuración, abre el área de Skills y sube el zip. Los nombres de los menús cambian con el tiempo, así que revisa los actuales.

### Claude Code

Copia la carpeta del idioma a `~/.claude/skills/`, o a `.claude/skills/` dentro de un solo proyecto.

### Otras herramientas de IA

La skill se hizo con Claude y se ha probado solo con Claude. El formato `SKILL.md` es un estándar abierto (agentskills.io), y otras herramientas dicen leerlo: revisa en la documentación de tu herramienta qué carpeta espera. Si tu herramienta no tiene carpeta de skills, pega el contenido del `SKILL.md`, debajo del bloque de cabecera, en el archivo de instrucciones del proyecto, como `AGENTS.md`.

### Personalízala

Añade un bloque como este a tu `CLAUDE.md`, a tu brief, o simplemente díselo a Claude en la conversación:

    ## Diseño sin cara de IA: ajustes
    Añadir a evitar: notas adhesivas, tarjetas de estadísticas redondeadas
    Liberar (no hace falta quitar): píldoras de estado
    Alternativas preferidas: una línea simple en lugar de la barra entre elementos del menú

Si no hay ajustes, la skill pregunta una vez y anota tu respuesta en este bloque.

## :memo: Licencia

Publicada bajo la licencia MIT. Puedes usarla, copiarla, adaptarla y compartirla, siempre que mantengas el aviso de derechos de autor. Consulta el archivo [LICENSE](LICENSE).
