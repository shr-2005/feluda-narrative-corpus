# Feluda Narrative-Function Corpus

This repository contains the sentence-level annotated corpus developed for the research paper **"A Fine-Grained Bengali Corpus Study on Feluda’s Detective Fiction."**

## Corpus overview

The corpus consists of **35 Feluda stories by Satyajit Ray**, represented at the sentence level. Each sentence is annotated using one of **13 narrative-function categories** by three annotators.

The released CSV contains the sentence text together with the three annotators' labels.

### Corpus statistics

- Stories: 35
- Sentences: 50,238
- Word tokens: 433,130
- Characters excluding whitespace: 2,209,327
- Mean sentence length: 8.62 words
- Maximum sentence length: 101 words
- Annotators: 3
- Narrative-function categories: 13

## File structure

```text
feluda-narrative-corpus/
├── README.md
├── data/
│   └── feluda_annotated.csv
└── docs/
    └── annotation_guidelines.md
```

## Data format

`data/feluda_annotated.csv` contains the following columns:

| Column | Description |
|---|---|
| `Story Name` | Name of the Feluda story |
| `Sentence ID` | Sentence identifier in the corpus |
| `Sentence` | Bengali sentence text |
| `Annotator 1` | Narrative-function label assigned by annotator 1 |
| `Annotator 2` | Narrative-function label assigned by annotator 2 |
| `Annotator 3` | Narrative-function label assigned by annotator 3 |

## Narrative-function categories

The corpus uses the following 13 categories:

1. Dialogue
2. Narration / Observation
3. Setting / Scene Description
4. Detective Reasoning / Deduction
5. Travel / Movement
6. Character Description
7. Backstory / Exposition
8. Character Introduction
9. Investigation Action
10. Crime / Threat / Violence
11. Clue / Evidence
12. Emotional Reaction
13. Suspense / Tension

Detailed descriptions of the categories are provided in [`docs/annotation_guidelines.md`](docs/annotation_guidelines.md).

## Corpus construction

The corpus was constructed from a collection of Satyajit Ray's works obtained from the eBanglaLibrary author collection. The collected material was cleaned and processed, after which the Feluda stories were identified and compiled into a single corpus. The resulting stories were sentence-segmented and annotated at the sentence level by three annotators.

The scraping and annotation application were used as supporting stages of the corpus-development process. They are not required for using the released annotated dataset and are therefore not included as primary resources in this repository.

## Source material

The literary source material was obtained from the Satyajit Ray author collection at eBanglaLibrary:

https://www.ebanglalibrary.com/authors/সত্যজিৎ-রায়/

This repository focuses on the resulting annotated corpus. The original collection of 47 Satyajit Ray books used during corpus construction is not included.

## Citation

If you use this dataset, please cite the associated research paper:

> Apurba Paul, Shrotriya Ghosh, Aniruddha Maiti, and Shouvik Maity. *A Fine-Grained Bengali Corpus Study on Feluda’s Detective Fiction.*

A formal citation entry can be added after the paper is published.

## License and copyright

The repository should be used in accordance with the rights applicable to the underlying literary material and the terms of the source from which it was collected. The presence of text in this research resource does not imply that the underlying literary works are in the public domain.

Before public distribution, users and maintainers should verify that redistribution of the included sentence text is permitted.
