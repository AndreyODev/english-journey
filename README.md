# English Journey

Este repositório organiza e documenta minha jornada de estudos de inglês. Ele reúne registros de diferentes fontes, ajuda a acompanhar minha evolução ao longo do tempo e funciona como uma base de consulta.

## Como estudo

O caderno físico continua sendo a parte principal do estudo. Depois de estudar, posso registrar aqui um resumo, vocabulário, observações ou dificuldades e, quando fizer sentido, incluir uma foto da página do caderno. Não é necessário transcrever tudo: o registro digital complementa o caderno, não o substitui.

## Fontes de estudo

- [Course](COURSE/): registros do curso principal, organizados por temporada.
- [Books](BOOKS/): leituras e estudos feitos a partir de livros em inglês.
- [Music](MUSIC/): estudos de músicas, organizados por música.
- [Series](SERIES/): estudos de episódios de séries e filmes, organizados por obra, temporada e episódio.
- [Grammar](GRAMMAR/): referências centralizadas para revisão rápida de gramática.

## Estrutura

```text
english-journey/
├── README.md
├── COURSE/
│   └── jornada-zero-fluencia/
│       ├── season-01/
│       ├── season-02/
│       └── season-03/
├── BOOKS/
├── MUSIC/
├── SERIES/
├── GRAMMAR/
└── IMAGES/
```

- `COURSE/`: curso principal, separado por seasons. Os registros futuros devem ter nomes que indiquem o assunto, como `present-simple.md`, em vez de depender apenas de números de dias.
- `BOOKS/`: uma pasta por livro, com registros por capítulo quando necessário.
- `MUSIC/`: um arquivo Markdown por música estudada.
- `SERIES/`: uma pasta por série ou filme; temporadas e episódios podem ser organizados em níveis próprios.
- `GRAMMAR/`: notas de referência por assunto gramatical.
- `IMAGES/`: fotos das páginas do caderno, separadas por ano e mês quando houver imagens reais.

As pastas de seasons iniciais são apenas a estrutura do curso. Livros, músicas, séries, episódios e estudos serão adicionados conforme forem estudados.

## Grammar

A gramática será aprendida naturalmente por meio do curso, dos livros, das músicas e das séries. `GRAMMAR/` não é uma fonte de estudo isolada: é um índice de consulta, com uma nota por assunto para facilitar revisões futuras sem precisar lembrar onde o tema apareceu pela primeira vez. Quando útil, a nota pode apontar para os registros em que o assunto foi encontrado.

## Imagens do caderno

As fotos ficam fisicamente em `IMAGES/`, organizadas em `ano/mês` quando forem adicionadas. Um nome como `2026/09/02-course.jpg` combina data e contexto para facilitar a identificação. A foto é incorporada no Markdown do estudo correspondente usando um caminho relativo calculado a partir da localização desse arquivo. Por exemplo, em um registro dentro de `COURSE/jornada-zero-fluencia/season-01/`:

```markdown
## My notebook

![My study](../../../IMAGES/2026/09/02-course.jpg)
```

## Modelo de registro

Use somente as seções que ajudarem; o registro deve ser simples e sustentável.

```markdown
# [Study topic]

**Date:** [date]  
**Source:** [course, book, music, series, or other context]  
**Study time:** [optional]

## What I studied

[Brief summary]

## Vocabulary

- [word or expression] — [meaning or note]

## What I understood

[Optional notes]

## Difficulties

[Optional notes]

## My notebook

![My study](../../../IMAGES/[year]/[month]/[date-context].jpg)
```

O caminho da imagem no modelo é um exemplo para registros em `COURSE/jornada-zero-fluencia/season-01/`. Em outras áreas, ajuste `../` conforme a profundidade do arquivo Markdown.