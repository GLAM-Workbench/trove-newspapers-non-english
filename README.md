# Trove newspapers in languages other than English

Current version: [v1.1](https://github.com/GLAM-Workbench/trove-newspapers-non-english/releases/tag/v1.1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12697210.svg)](https://doi.org/10.5281/zenodo.12697210.)

This dataset contains information about newspapers published in languages other than English that have been digitised and made available through Trove. Data about the languages present in newspapers was generated by harvesting a sample of articles from each newspaper using the Trove API, and then using language detection software on the OCRd text of each article. The method is documented in [this notebook](https://glam-workbench.net/trove-newspapers/find-non-english-newspapers/) in the GLAM Workbench.

There are two files:

- `newspapers_non_english.csv` – list of the main languages detected for each newspaper with non-English language content
- `non-english-newspapers.md` – a markdown formatted list of all the newspapers with non-English language content

## `newspapers_non_english.csv`

The dataset contains the following columns:

| Column | Contents |
|--------|----------|
`id` | newspaper id
`title` | newspaper title
`language` | language code
`proportion` | proportion of articles in this language
`number` | number of articles sampled
`language_full` | full language name

## `non-english-newspapers.md`

This is [a markdown-formatted list](https://github.com/GLAM-Workbench/trove-newspapers-non-english/blob/main/non-english-newspapers.md) created by grouping the dataset by newspaper title. It includes details of the main languages in each newspaper.



