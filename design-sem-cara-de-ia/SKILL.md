---
name: "design-sem-cara-de-ia"
description: "Use ao desenhar ou codar templates, sites e outros materiais gráficos (cartazes, slides, posts, banners, capas) para evitar o visual genérico de IA: identidade própria, vícios padrão personalizáveis, texto realista e revisão final."
---

# Design sem cara de IA

Use esta skill sempre que for desenhar qualquer material gráfico (site ou template, cartaz, slide, post, banner, capa), materializar um design em uma ferramenta (Figma, Canva etc.) ou transformar um design em código. O objetivo: cada projeto tem identidade própria, não parece saído de um gerador e não parece parecido com outro projeto da mesma pessoa.

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
2. Qual é o esqueleto (ordem e forma das seções, ou dos elementos numa peça única)? Ele difere dos projetos já feitos?
3. Qual é a paleta (3 a 5 cores, cada uma com função) e a tipografia (no máximo 2 famílias)? Nenhuma repete a de outro projeto?
4. Qual é o elemento de marca? Algo feito só para este conceito, que não faria sentido em outro.

Se esqueleto, paleta ou tipografia forem parecidos com outro projeto, mude antes de continuar.

Se não houver outros projetos à vista, peça uma referência ou pule a comparação e avise que pulou.

Se a pessoa já tem cores, fontes ou logo de marca, essa é a identidade. Use-os e construa o resto (composição, formas, tom) em torno deles. A pergunta 3 passa a ser: quais cores e fontes da marca eu uso, e para qual função?

Exemplo das respostas por escrito, para um cartaz do concerto de outono de um coral comunitário (sem marca ainda; o texto do exemplo fica em inglês):

1. Universe: sheet music, breath, wooden church benches, October light.
2. Skeleton: one tall piece. The date and place come first and big, the program is a staggered list, the ticket line sits at the bottom. Not a centered title with a button.
3. Palette: ink brown for text, pumpkin for the date, cream for the paper, moss for small details. One serif for the choir's name and one plain sans for everything else.
4. Brand element: a row of singers drawn as simple shapes that grow from left to right like a rising scale. It would make no sense on any other piece.

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

## Outros formatos

Tudo o que está acima vale para qualquer formato: cartaz, slide, post, banner, capa e template de site. Identidade, texto realista e revisão final não mudam. Onde uma regra foi escrita para sites, é assim que ela se lê em outros formatos:

| Em um site ou template | Em outros formatos |
|---|---|
| Seções e a ordem delas | A ordem e o agrupamento dos elementos na peça: o que se lê primeiro, depois e por último, ou os slides de uma apresentação em sequência |
| Uma ideia visual por seção | Uma ideia visual por página, slide ou painel |
| Espaços de foto vazios e fáceis de trocar | Um quadro vazio ou caixa provisória claramente marcada, no tamanho que a foto precisa |
| HTML semântico, variáveis CSS no topo | Estilos nomeados, camadas e cores de tema, para trocar uma cor ou uma fonte em um lugar só |
| Arte de marca em SVG, não em imagem raster | Arte de marca em formas vetoriais, não em imagens achatadas |
| Menus, rodapés e cards | Cabeçalhos, rodapés, legendas, créditos e rótulos |
| Animação com propósito | Movimento só onde o formato tem (transições de slide, vídeo, banner animado), com propósito ligado ao conceito |
| Fidelidade a um design existente | Se você converte um design aprovado para outro formato ou ferramenta, mantenha o mesmo conteúdo, ordem, cores e fontes |

## Revisão final (antes de mostrar)

1. Confira item por item os ajustes da pessoa e a lista de vícios acima. Procure em especial pílulas esquecidas, números, barras e travessões em menus, rodapés, cards e textos de apoio.
2. Teste do logo: se eu tirasse o logo, alguém saberia de qual projeto é? Se não, falta identidade.
3. Teste da vizinhança: coloque ao lado de outro projeto da mesma pessoa. Se trocar o nome e a cor bastasse para confundir os dois, refaça o esqueleto. Se não houver outro trabalho à vista, peça uma referência ou pule este teste e avise que pulou.
4. Reporte o que encontrou e o que mudou.
