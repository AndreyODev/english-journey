# English Journey

[🇧🇷 Português](README.pt-BR.md)

This repository stores my English study notes. It helps me keep notes from different study sources, follow my progress over time, and find things I want to review.

## How I study

My paper notebook is still the main part of my study. After a study session, I can write a short summary here, add new words, notes, or difficulties, and include a photo of the notebook page when it helps. I do not need to copy everything. The notes here support my notebook; they do not replace it.

## Study sources

- [Course](COURSE/): notes from my main English course, organized by season.
- [Books](BOOKS/): notes about books I read in English.
- [Music](MUSIC/): notes about songs I study.
- [Series](SERIES/): notes about TV shows and movies, organized by title, season, and episode.
- [Grammar](GRAMMAR/): one place to find and review grammar notes.

## Folders

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

- `COURSE/`: my main course, organized by season. Future note names should describe the topic, such as `present-simple.md`, instead of using only day numbers.
- `BOOKS/`: one folder for each book, with chapter notes when useful.
- `MUSIC/`: one Markdown file for each song I study.
- `SERIES/`: one folder for each show or movie. Seasons and episodes can have their own folders and notes.
- `GRAMMAR/`: reference notes for grammar topics.
- `IMAGES/`: photos of my notebook pages, organized by year and month when I add them.

The season folders are only the starting structure for the course. I will add books, songs, shows, episodes, and study notes as I study them.

## Grammar

I learn grammar through my course, books, songs, and shows. `GRAMMAR/` is not a separate study source. It is a place to keep one note for each topic, so I can review it later without having to remember where I first saw it. When useful, a grammar note can link to the study notes where I found that topic.

## Notebook photos

Photos are stored in `IMAGES/` and can be organized by year and month when I add them. A name like `2026/09/02-course.jpg` includes the date and the study source. The photo is added to the Markdown note with a relative path. For example, this path works from a note in `COURSE/jornada-zero-fluencia/season-01/`:

```markdown
## My notebook

![My study](../../../IMAGES/2026/09/02-course.jpg)
```

## Study note template

Use only the sections that are helpful. Keep each note simple and easy to maintain.

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

The image path in this template is an example for a note in `COURSE/jornada-zero-fluencia/season-01/`. In other folders, change the `../` parts to match the location of the Markdown file.
