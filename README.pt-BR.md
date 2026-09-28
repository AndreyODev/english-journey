# English Journey

[🇺🇸 English](README.md)

Este repositório guarda minhas anotações de estudo de inglês. Ele me ajuda a reunir registros de diferentes fontes, acompanhar minha evolução ao longo do tempo e encontrar assuntos para revisar.

## Como estudo

Meu caderno físico continua sendo a parte principal do estudo. Depois de uma sessão, posso escrever aqui um resumo curto, adicionar palavras novas, observações ou dificuldades e incluir uma foto da página do caderno quando ajudar. Não preciso copiar tudo. As anotações daqui apoiam o caderno, mas não o substituem.

## Fontes de estudo

- [Course](COURSE/): anotações do meu curso principal de inglês, organizadas por temporada.
- [Books](BOOKS/): anotações sobre livros que leio em inglês.
- [Music](MUSIC/): anotações sobre músicas que estudo.
- [Series](SERIES/): anotações sobre séries e filmes, organizadas por título, temporada e episódio.
- [Grammar](GRAMMAR/): um lugar para encontrar e revisar anotações de gramática.

## Pastas

```text
english-journey/
├── README.md
├── README.pt-BR.md
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

- `COURSE/`: meu curso principal, organizado por temporada. Os nomes das futuras anotações devem indicar o assunto, como `present-simple.md`, em vez de usar apenas números de dias.
- `BOOKS/`: uma pasta para cada livro, com anotações por capítulo quando forem úteis.
- `MUSIC/`: um arquivo Markdown para cada música estudada.
- `SERIES/`: uma pasta para cada série ou filme. Temporadas e episódios podem ter suas próprias pastas e anotações.
- `GRAMMAR/`: anotações de referência sobre assuntos gramaticais.
- `IMAGES/`: fotos das páginas do caderno, organizadas por ano e mês quando forem adicionadas.

As pastas de temporada são apenas a estrutura inicial do curso. Livros, músicas, séries, episódios e anotações serão adicionados conforme forem estudados.

## Grammar

Aprendo gramática por meio do curso, dos livros, das músicas e das séries. `GRAMMAR/` não é uma fonte de estudo separada. É um lugar para guardar uma anotação de cada assunto e poder revisá-lo depois sem precisar lembrar onde o encontrei pela primeira vez. Quando for útil, uma anotação de gramática pode apontar para os registros de estudo em que encontrei aquele assunto.

## Fotos do caderno

As fotos ficam em `IMAGES/` e podem ser organizadas por ano e mês quando forem adicionadas. Um nome como `2026/09/02-course.jpg` inclui a data e a fonte de estudo. A foto é incluída na anotação Markdown usando um caminho relativo. Por exemplo, este caminho funciona em uma anotação dentro de `COURSE/jornada-zero-fluencia/season-01/`:

```markdown
## My notebook

![My study](../../../IMAGES/2026/09/02-course.jpg)
```

## Modelo de anotação

Use somente as seções que forem úteis. Mantenha cada anotação simples e fácil de atualizar.

```markdown
# [Study topic]

**Date:** [date]  
**Source:** [course, book, song, show, or other source]  
**Study time:** [optional]

## What I studied

[Short summary]

## Vocabulary

- [word or phrase] — [meaning or note]

## What I understood

[Optional notes]

## Difficulties

[Optional notes]

## My notebook

![My study](../../../IMAGES/[year]/[month]/[date-context].jpg)
```

O caminho da imagem neste modelo é um exemplo para uma anotação em `COURSE/jornada-zero-fluencia/season-01/`. Em outras pastas, ajuste as partes `../` de acordo com a localização do arquivo Markdown.
