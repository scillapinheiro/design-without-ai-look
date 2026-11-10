---
name: "design-sem-cara-de-ia"
description: "Use ao desenhar ou codar templates, sites e outros materiais gráficos (cartazes, slides, posts, banners, capas) para que o resultado tenha identidade própria em vez do visual genérico de IA: decisões escritas antes de desenhar, vícios padrão personalizáveis, texto realista e uma revisão final que dá para executar."
---

# Design sem cara de IA

Use esta skill sempre que for desenhar qualquer material gráfico (site ou template, cartaz, slide, post, banner, capa), materializar um design em uma ferramenta (Figma, Canva etc.) ou transformar um design em código. O objetivo: dar a cada projeto mais chance de ter identidade própria, que não seja o padrão de um gerador.

## Passo 0: ajustes da pessoa (valem mais que qualquer regra abaixo)

A lista de vícios desta skill é um ponto de partida. A pessoa pode mudar de três jeitos:

1. **Acrescentar** proibições próprias (um enfeite que apareceu demais, uma forma, um hábito de texto).
2. **Liberar** vícios padrão que ela não quer tirar (por exemplo, "pode usar pílulas" ou "pode usar barras").
3. **Trocar a alternativa** sugerida para um vício, se ela preferir outra.

Procure esses ajustes em CLAUDE.md, AGENTS.md ou no arquivo de instruções que a ferramenta lê, no README, no briefing ou na conversa, em um bloco como este:

```
## Design sem cara de IA: ajustes
Acrescentar a evitar: ...
Liberar (não precisa tirar): ...
Alternativas preferidas: ...
```

Se não houver ajustes, pergunte uma vez, na mesma mensagem da pergunta de gosto do Passo 1, para que a pessoa receba uma mensagem e não duas: "Quer acrescentar algo que você não quer ver, ou liberar algum dos vícios padrão? E como você gosta que seja? Formas, cores, densidade, o que te parece bonito e o que te parece feio.". Se a pessoa responder só uma das duas perguntas, use a resposta que veio e valem os vícios padrão para o resto. Anote os ajustes no bloco acima e siga em todo o projeto. Repita as regras valendo no início do trabalho.

## Passo 1: identidade antes do layout

Antes de escolher qualquer coisa, você precisa do gosto da pessoa em uma frase. Ele é pedido na mensagem do Passo 0 acima; se os ajustes foram encontrados em um arquivo e o Passo 0 não perguntou nada, pergunte só isto, por exemplo: "Como você gosta que seja? Formas, cores, densidade, o que te parece bonito e o que te parece feio." Se ela tiver referências, use. Se não tiver, essa frase basta. Só desenhe sem nada disso se a pessoa disser que não tem preferência. Se um briefing, uma marca ou respostas anteriores já mostram o gosto dela, use isso e não pergunte de novo. Por quê: nos testes, sem nenhum gosto informado o resultado caiu na média do que "parece bom design", e com uma frase de gosto ficou muito melhor.

Antes das quatro respostas abaixo, escreva três direções, em uma ou duas linhas cada. Se a pessoa não deu referências, derive as direções do conteúdo real do produto (seus objetos, lugar, clientes, o que de fato vai estar na página) e faça com que difiram em pelo menos três destes eixos: densidade, temperatura de cor, voz da tipografia, linguagem de forma. Cada eixo precisa diferir por categoria e de forma perceptível (quente ou frio, esparso ou denso, serifa ou sans arredondada, curva ou ortogonal), e não por grau (um pouco mais quente, um pouco mais denso). Confira cada par de direções: se dois dos eixos que você está contando diferirem pouco, reforce esses eixos ou troque a direção. Uma descrição diferente não basta, as escolhas em si precisam diferir. Cada direção deve ser justificada pelo negócio, e não só por ser diferente das outras: diferente mas incoerente também falha. Escolha uma e diga por quê; as quatro respostas abaixo valem para ela.

Depois responda por escrito, antes de desenhar, para a direção que você escolheu:
1. Qual é o universo real do conceito (objetos, materiais, lugares, época, sons)? Parta do que a pessoa teria de fato à mão, como o balcão de um dono ou o piano de uma professora, e não de uma metáfora de design.
2. Qual é o esqueleto (ordem e forma das seções, ou dos elementos numa peça única)?
3. Qual é a paleta (3 a 5 cores, cada uma com função) e a tipografia (escolhida como diz o parágrafo de tipografia abaixo)?
4. Qual é o elemento de marca? Algo feito só para este conceito, que não faria sentido em outro.

Se a pessoa já tem cores, fontes ou logo de marca, essa é a identidade. Use-os e construa o resto (composição, formas, tom) em torno deles. A pergunta 3 passa a ser: quais cores e fontes da marca eu uso, e para qual função?

Exemplo das respostas por escrito, para um cartaz do concerto de outono de um coral comunitário (sem marca ainda; o texto do exemplo fica em inglês):

1. Universe: sheet music, breath, wooden church benches, October light.
2. Skeleton: one tall piece. The date and place come first and big, the program is a staggered list, the ticket line sits at the bottom. Not a centered title with a button.
3. Palette: ink brown for text, pumpkin for the date, cream for the paper, moss for small details. One serif for the choir's name (headlines) and one plain sans for the program and the ticket line (text and data).
4. Brand element: a row of singers drawn as simple shapes that grow from left to right like a rising scale. It would make no sense on any other piece.

Tipografia. Use as famílias que o conceito pedir e justifique cada uma pela função (títulos, texto, dados). Siga esta ordem. Primeiro escreva o que o texto pequeno precisa fazer (preços, datas, legendas, letras miúdas) e onde ele será lido, porque isso define o que a família precisa aguentar. Depois proponha três candidatas (pares ou famílias únicas) ligadas ao universo do conceito, como a mão de um pintor de letreiros, um livro-caixa, um hinário, e diga por que cada uma serve. Escolha uma e diga por quê. Ao escolher a família, confira se ela tem ã, ç, é e ô completos, nos pesos que você vai usar. Não comece pelas duplas de reflexo dadas como exemplo nos vícios abaixo.

## Passo 2: decidir antes de desenhar

Escreva estas decisões, com números reais, antes de desenhar. Elas também são a lista de conferência da revisão final.

| Decisão | O que escrever |
|---|---|
| Elemento dominante | A única coisa sobre a qual cada tela ou página é, e o que dá espaço a ela |
| Escala tipográfica | Tamanhos reais de título, subtítulo, corpo e texto pequeno (por exemplo 72, 32, 18 e 14), com o título várias vezes maior que o corpo |
| Unidade de espaçamento | Uma unidade base (por exemplo 8) e os poucos múltiplos que você vai usar |
| Três movimentos de composição | Três escolhas que moldam o layout, como uma âncora fora do centro, um corte deliberado ou uma mudança de densidade entre seções. Não são enfeite |

## Vícios que entregam o trabalho de IA (cada um pode ser liberado no Passo 0)

O princípio vem antes da lista: se a sua primeira ideia serviria para qualquer negócio do mesmo tipo, descarte e recomece a partir deste negócio.

**Pílulas de status e etiquetas.** Etiquetas arredondadas como "NEW", "ON SALE", "LIVE", tags de categoria usadas como enfeite. Alternativa: texto simples bem posicionado, ou um elemento do universo real do conceito. Não repita a mesma alternativa em seções vizinhas. Uma etiqueta só vale quando carrega informação que o visitante precisa naquele ponto. Por quê: geradores põem etiqueta de status em todo bloco para parecer movimento e novidade, e uma etiqueta sem informação nova é só ruído.

**Numeração.** Números de página, de seção ou de card ("01", "02", "Page 2 of 5"), contadores decorativos e estatísticas sem fonte. Dados reais necessários (datas, horários, durações, preços) podem. Por quê: números sugerem um processo ou um ranking que o conteúdo não tem, e estatísticas sem fonte parecem inventadas.

**Rótulo minúsculo em caixa alta** sobre título grande, repetido em toda seção. Alternativa: um título que se sustenta sozinho. Por quê: é um gesto pronto para criar hierarquia e, repetido em toda seção, vira carimbo de template.

**Brilhos e glows**, sombras coloridas difusas, degradês roxo e azul genéricos. Alternativa: cor chapada com uma função clara. Por quê: são o padrão de modelos de imagem e de degradês prontos, então dizem "gerado" à primeira vista.

**Grade de três cards iguais** com ícone, título e frase. Alternativa: um layout feito para o conteúdo. Por quê: preenche uma fileira sem decidir o que importa, e a grade molda o conteúdo em vez do contrário.

**Ícones de linha genéricos** no lugar de arte pensada para o conceito. Por quê: vêm dos mesmos poucos conjuntos de ícones que todo mundo usa, então não dizem nada sobre este conceito.

**Frases vagas de marketing** ("Elevate your sound", "Crafted with passion") e **lorem ipsum**. Escreva texto específico, com nome, lugar e data plausíveis. Por quê: uma frase que descreveria qualquer produto não descreve nenhum, e texto provisório esconde se o layout funciona com palavras reais.

**Escolher a dupla de fontes por reflexo.** O vício é escolher a dupla sem pensar, e não a dupla em si: nenhuma fonte é proibida. Alternativa: as candidatas que você propôs no Passo 1, ligadas ao conceito. Por quê: as fontes que aparecem primeiro em trabalho gerado dizem "padrão" antes de alguém ler uma palavra. Se o conceito justificar uma delas pela função (títulos, texto, dados), use e diga por quê. Exemplos de duplas a que os modelos recorrem (um palpite para a autora revisar, e uma lista que envelhece como os exemplos abaixo): Playfair Display com Inter ou Lato, Fraunces com Inter, DM Serif Display com DM Sans, Cormorant Garamond com Montserrat, Space Grotesk para tudo, Poppins ou Montserrat sozinhas para tudo, Inter sozinha.

**Ilustrar onde a pessoa vai colocar a própria foto.** Ilustração é arte de marca; espaço de foto fica vazio e fácil de trocar. Por quê: a pessoa vai trocar de qualquer jeito, e isso esconde que ainda falta uma foto.

**A mesma composição em todas as seções** (título central, botão abaixo, imagem ao fundo). Alternativa: uma ideia visual por seção. Por quê: repetir um layout faz a página parecer uma ideia só esticada.

## Implicâncias da autora (ligadas por padrão, libere à vontade)

Estas são mais questão de gosto do que sinal de IA. Vêm ligadas por padrão porque a autora da skill não gosta delas. Libere qualquer uma no Passo 0.

**Barras como separador.** Barra simples ("/") ou dupla ("//") entre palavras, em menus, rótulos, datas ou créditos. Alternativa: espaço, ponto médio, linha, ou um elemento do conceito. Por quê: é um enfeite no lugar de um separador, comum em menus, datas e créditos gerados.

**Travessões no texto.** Use vírgula, ponto ou dois pontos. Por quê: travessões longos são um dos hábitos mais reconhecíveis de texto gerado.

**Serifada itálica** como "toque elegante" automático. Por quê: é um jeito automático de parecer elegante que aparece em muito trabalho gerado.

## Exemplos observados em testes (uma lista aberta que envelhece)

Vistos em novembro de 2026 com o Claude Sonnet 5.5, no pedido "primeira tela de uma padaria de bairro". Os modelos mudam, então leia isto como uma amostra de padrões, e não como uma lista completa.

- Sem a skill: fundo creme com marrom e terracota, título em serifa com uma palavra em outra cor, hero em duas colunas com o objeto num retângulo arredondado à direita, um card ou etiqueta flutuante, um par de botões (um cheio, um com contorno), um rodapé em faixa com três colunas.
- Com uma versão anterior desta skill: o mesmo objeto "bilhete, carimbo ou comanda" em todos os resultados (a lista de alternativas virou o próximo vício), linhas decorativas soltas, uma palavra recolorida no título, um botão com sombra dura.
- Com uma regra que dizia "mude paleta, tipografia e estrutura de propósito": o extremo oposto, um nome gigante sobre uma cor chapada saturada, uma ideia só gritando. Um resultado ficou com o título cortado e outro com uma grande área vazia, porque ninguém renderizou o resultado.

## Fazer

- Cada seção tem uma ideia visual própria ligada ao conceito, não só um bloco de texto sobre fundo.
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
2. Confira o resultado contra as decisões do seu Passo 2: elemento dominante, escala tipográfica, unidade de espaçamento, três movimentos de composição.
3. Se puder renderizar, renderize em tamanho de desktop e de celular e rode os seis primeiros testes abaixo. Se não puder, diga que não conferiu o resultado visual. O último teste vale sempre.
4. Reporte o que encontrou e o que mudou.

| Teste | O que procurar |
|---|---|
| Desfoque | Desfoque ou aperte os olhos para o render: a hierarquia ainda aparece? |
| Cinza | Tire a cor: a página ainda se sustenta? |
| Troca | Coloque o texto de outro negócio: se nada na página reclama, ela é genérica |
| Contagem | Tamanhos de fonte, cores e componentes repetidos: mais do que você decidiu no Passo 2? |
| Corte e vazio | Texto cortado pela borda, sobreposições, grandes áreas vazias |
| Troca de fonte | Troque a fonte de título pela dupla de reflexo mais próxima do estilo escolhido (por exemplo, Poppins 800 para um título arredondado e pesado): se a página fica igual ou melhor, a escolha da fonte não está trabalhando pelo conceito |
| Logo | Tire o logo: alguém saberia de qual projeto é? Se não, falta identidade |
