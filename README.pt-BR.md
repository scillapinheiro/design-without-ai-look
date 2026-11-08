<h1 align="center">Design sem cara de IA</h1>

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.pt-BR.md">Português</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <a href="#computer-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-como-funciona">Como funciona</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sparkles-o-que-ela-evita">O que ela evita</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#eyes-como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="Licença" src="https://img.shields.io/static/v1?label=licen%C3%A7a&message=MIT&color=6D4FD8&labelColor=grey">
  <img alt="Tipo" src="https://img.shields.io/static/v1?label=tipo&message=skill%20do%20Claude&color=137A67&labelColor=grey">
  <img alt="Idiomas" src="https://img.shields.io/static/v1?label=idiomas&message=EN%20%C2%B7%20PT%20%C2%B7%20ES&color=lightgrey&labelColor=grey">
</p>

## :computer: Projeto

**Design sem cara de IA** é uma skill para o Claude que ajuda você a desenhar e programar templates e sites que não parecem feitos por IA.

Ela nasceu de um problema real: muita gente quer fazer templates com IA, e os resultados têm todos os mesmos vícios. Pílulas de status em tudo, seções numeradas, barras decorativas, três cards iguais em fila, um brilho atrás do título. Cada um é pequeno, mas juntos entregam o trabalho.

A skill dá ao Claude uma lista padrão desses vícios a evitar, pede que ele defina uma identidade para cada projeto antes de desenhar qualquer coisa e termina com uma revisão.

## :bulb: Como funciona

- **Os seus ajustes vêm primeiro.** A lista padrão é um ponto de partida. Você pode acrescentar o que não quer ver, liberar vícios padrão de que gosta e trocar a alternativa sugerida para qualquer um.
- **Identidade antes do layout.** Antes de desenhar, o Claude responde por escrito: qual é o universo do conceito, qual é o esqueleto, qual paleta e tipografia, e qual é o elemento de marca que não faria sentido em outro projeto.
- **Uma lista de vícios, cada um com alternativa.** Não só "não faça isso", mas o que fazer no lugar.
- **Uma revisão final.** Um teste do logo (sem o logo, alguém saberia de quem é o projeto?) e um teste da vizinhança (ao lado de outro projeto seu, é fácil confundir os dois?).

## :sparkles: O que ela evita

Estes são os padrões. Todos podem ser liberados.

| Vício | No lugar |
|---|---|
| Pílulas de status e etiquetas decorativas | Texto simples bem posicionado, ou um elemento do universo do conceito |
| Numeração de página, seção e card | Só dados reais: datas, horários, durações, preços |
| Barras como separador | Um espaço, um ponto médio, uma linha |
| Travessões no texto | Vírgula, ponto ou dois pontos |
| Rótulo minúsculo em caixa alta sobre título grande | Um título que se sustenta sozinho |
| Brilhos, glows, degradês roxo e azul genéricos | Cor chapada com uma função clara |
| Três cards iguais com ícone, título e frase | Um layout feito para o conteúdo |
| Frases vagas de marketing e lorem ipsum | Texto específico, com nomes, lugares e datas plausíveis |
| A mesma composição em todas as seções | Uma ideia visual por seção |

A lista completa, com os motivos, está no arquivo da skill.

## :eyes: Como usar

O repositório tem três pastas com a mesma skill em três idiomas.

| Idioma | Pasta |
|---|---|
| English | `design-without-ai-look` |
| Português | `design-sem-cara-de-ia` |
| Español | `diseno-sin-cara-de-ia` |

**Instale só uma.** Se instalar mais de uma, o Claude carrega todas ao mesmo tempo.

### Claude (app e site)

1. Baixe este repositório (**Code, Download ZIP**) e descompacte.
2. Compacte em zip a pasta do idioma que você quer. A pasta precisa ter o `SKILL.md` no nível de cima.
3. Em Configurações, abra a área de Skills e envie o zip. Os nomes dos menus mudam com o tempo, então confira os atuais.

### Claude Code

Copie a pasta do idioma para `~/.claude/skills/`, ou para `.claude/skills/` dentro de um projeto só.

### Personalize

Coloque um bloco como este no seu `CLAUDE.md`, no briefing, ou apenas diga ao Claude na conversa:

    ## Design sem cara de IA: ajustes
    Acrescentar a evitar: post-its, cards de estatística arredondados
    Liberar (não precisa tirar): pílulas de status
    Alternativas preferidas: uma linha simples no lugar da barra entre itens do menu

Se não houver ajustes, a skill pergunta uma vez e anota a sua resposta nesse bloco.

## :memo: Licença

Publicada sob a licença MIT. Você pode usar, copiar, adaptar e compartilhar, desde que mantenha o aviso de direitos autorais. Veja o arquivo [LICENSE](LICENSE).
