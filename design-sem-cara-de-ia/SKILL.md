---
name: "design-sem-cara-de-ia"
description: "Use ao desenhar ou codar templates e sites para evitar o visual genérico de IA: identidade própria, vícios padrão personalizáveis, texto realista e revisão final."
---

# Design sem cara de IA

Use esta skill sempre que for desenhar um layout, materializar um design em uma ferramenta (Figma, Canva etc.) ou transformar um design em código. O objetivo: cada projeto tem identidade própria, não parece saído de um gerador e não parece parecido com outro projeto da mesma pessoa.

## Passo 0: ajustes da pessoa (valem mais que qualquer regra abaixo)

A lista de vícios desta skill é um ponto de partida. A pessoa pode mudar de três jeitos:

1. **Acrescentar** proibições próprias (um enfeite que apareceu demais, uma forma, um hábito de texto).
2. **Liberar** vícios padrão que ela não quer tirar (por exemplo, "pode usar pílulas" ou "pode usar barras").
3. **Trocar a alternativa** sugerida para um vício, se ela preferir outra.

Procure esses ajustes em CLAUDE.md, README, briefing ou na conversa, em um bloco como este:

```
## Design sem cara de IA: ajustes
Acrescentar a evitar: ...
Liberar (não precisa tirar): ...
Alternativas preferidas: ...
```

Se não houver ajustes, pergunte uma vez, em uma frase: "Quer acrescentar algo que você não quer ver, ou liberar algum dos vícios padrão?". Anote a resposta no bloco acima e siga em todo o projeto. Repita as regras valendo no início do trabalho.

## Passo 1: identidade antes do layout

Responda por escrito, antes de desenhar:
1. Qual é o universo do conceito (objetos, materiais, lugares, época, sons)?
2. Qual é o esqueleto (ordem e forma das seções)? Ele difere dos projetos já feitos?
3. Qual é a paleta (3 a 5 cores, cada uma com função) e a tipografia (no máximo 2 famílias)? Nenhuma repete a de outro projeto?
4. Qual é o elemento de marca? Algo feito só para este conceito, que não faria sentido em outro.

Se esqueleto, paleta ou tipografia forem parecidos com outro projeto, mude antes de continuar.

## Vícios que entregam o trabalho de IA (cada um pode ser liberado no Passo 0)

**Pílulas de status e etiquetas.** Etiquetas arredondadas como "NEW", "ON SALE", "LIVE", tags de categoria usadas como enfeite. Alternativa: texto simples bem posicionado, ou um elemento do universo do conceito (selo, carimbo, bilhete, botão). Uma etiqueta só vale quando carrega informação que o visitante precisa naquele ponto. Por quê: geradores põem etiqueta de status em todo bloco para parecer movimento e novidade, e uma etiqueta sem informação nova é só ruído.

**Numeração.** Números de página, de seção ou de card ("01", "02", "Page 2 of 5"), contadores decorativos e estatísticas sem fonte. Dados reais necessários (datas, horários, durações, preços) podem. Por quê: números sugerem um processo ou um ranking que o conteúdo não tem, e estatísticas sem fonte parecem inventadas.

**Rótulo minúsculo em caixa alta** sobre título grande, repetido em toda seção. Alternativa: um título que se sustenta sozinho. Por quê: é um gesto pronto para criar hierarquia e, repetido em toda seção, vira carimbo de template.

**Brilhos e glows**, sombras coloridas difusas, degradês roxo e azul genéricos. Alternativa: cor chapada com uma função clara. Por quê: são o padrão de modelos de imagem e de degradês prontos, então dizem "gerado" à primeira vista.

**Grade de três cards iguais** com ícone, título e frase. Alternativa: um layout feito para o conteúdo. Por quê: preenche uma fileira sem decidir o que importa, e a grade molda o conteúdo em vez do contrário.

**Ícones de linha genéricos** no lugar de arte pensada para o conceito. Por quê: vêm dos mesmos poucos conjuntos de ícones que todo mundo usa, então não dizem nada sobre este conceito.

**Frases vagas de marketing** ("Elevate your sound", "Crafted with passion") e **lorem ipsum**. Escreva texto específico, com nome, lugar e data plausíveis. Por quê: uma frase que descreveria qualquer produto não descreve nenhum, e texto provisório esconde se o layout funciona com palavras reais.

**Ilustrar onde a pessoa vai colocar a própria foto.** Ilustração é arte de marca; espaço de foto fica vazio e fácil de trocar. Por quê: a pessoa vai trocar de qualquer jeito, e isso esconde que ainda falta uma foto.

**A mesma composição em todas as seções** (título central, botão abaixo, imagem ao fundo). Alternativa: uma ideia visual por seção. Por quê: repetir um layout faz a página parecer uma ideia só esticada.

## Implicâncias da autora (ligadas por padrão, libere à vontade)

Estas são mais questão de gosto do que sinal de IA. Vêm ligadas por padrão porque a autora da skill não gosta delas. Libere qualquer uma no Passo 0.

**Barras como separador.** Barra simples ("/") ou dupla ("//") entre palavras, em menus, rótulos, datas ou créditos. Alternativa: espaço, ponto médio, linha, ou um elemento do conceito. Por quê: é um enfeite no lugar de um separador, comum em menus, datas e créditos gerados.

**Travessões no texto.** Use vírgula, ponto ou dois pontos. Por quê: travessões longos são um dos hábitos mais reconhecíveis de texto gerado.

**Serifada itálica** como "toque elegante" automático. Por quê: é um jeito automático de parecer elegante que aparece em muito trabalho gerado.

## Fazer

- Cada seção tem uma ideia visual própria ligada ao conceito, não só um bloco de texto sobre fundo.
- Um elemento dominante por tela, com respiro em volta.
- Escala tipográfica com contraste real (título muito maior que corpo).
- Texto com voz de pessoa real: específico, curto, sem clichê.
- Contraste mínimo WCAG AA. Se houver um design ou briefing aprovado e ele falhar, avise a pessoa e proponha uma correção em vez de mudar sozinho.
- Se já existe um layout aprovado, respeite: se o código ou a revisão exigir mudar esse layout, pergunte antes.

## Código

- HTML semântico, variáveis CSS no topo para cores, fontes e medidas.
- Ao transformar um design existente em código, mantenha a fidelidade a ele: mesmas seções, ordem, textos, cores e fontes.
- Animação com propósito ligado ao conceito, não efeito de entrada genérico em tudo.
- Ilustrações e elementos de marca em SVG, não em imagem raster.

## Revisão final (antes de mostrar)

1. Confira item por item os ajustes da pessoa e a lista de vícios acima. Procure em especial pílulas esquecidas, números, barras e travessões em menus, rodapés, cards e textos de apoio.
2. Teste do logo: se eu tirasse o logo, alguém saberia de qual projeto é? Se não, falta identidade.
3. Teste da vizinhança: coloque ao lado de outro projeto da mesma pessoa. Se trocar o nome e a cor bastasse para confundir os dois, refaça o esqueleto.
4. Reporte o que encontrou e o que mudou.
