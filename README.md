<img src="icon.png" align="right" />

# DSW 2019 - DATASET SHOWCASE WORKSHOP ![GitHub repo size](https://img.shields.io/github/repo-size/marianaossilva/DSW2019.svg?color=d43f3a)

[MusicSet]: https://marianaossilva.github.io/DSW2019

> [MusicSet][MusicSet] - An Enhanced Music Dataset for Music Data Mining

## Dataset Information

This repository stores an open and enhanced dataset of musical elements (music, albums, and artists) suitable for music data mining. 

The attractive features of [MusicSet][MusicSet] include:
* Integration and centralization of different musical data sources
* Calculation of popularity scores and classification of hits and non-hits musical elements, varying from 1962 to 2018
* Enriched metadata for music, artists, and albums from the US popular music industry
* Availability of acoustic and lyrical resources
* Unrestricted access in two formats: SQL database and compressed .csv files

This is a **pre-publication release**. As such, this repository as well as the data are subject to change. 

### Dataset Statistics

---
**Data** | **# Records**
--- | ---
Songs | 20,772
Artists | 10,988
Albums | 25,378
Lyrics | 20,768
Acoustic Features | 20,728
Genres | 950
---

## Format and Usage

[MusicSet][MusicSet] is available in a public repository in two different formats

1. **Relational Database** 
	- **[musicset.sql]**:  SQL file that will create the relational database and subsequently loads all the information in the tables by a MySQL installation (XGB) 
2. **.csv Tables**
	- **[musicset_metadata.zip]**: Contains textual and numeric information about songs, artists, and albums (XGB)
	- **[musicset_popularity.zip]**: Contains nine tables of musical popularity information (XGB)
	- **[musicset_songfeatures.zip]**: Contains lyrics and acoustic fingerprints of the songs collected (XGB)

[musicset.sql]: https://drive.google.com/open?id=0BxcdZUa_SVMcdzhLeWJuREd0UW8
[musicset_metadata.zip]: https://drive.google.com/open?id=0BxcdZUa_SVMcdzhLeWJuREd0UW8
[musicset_popularity.zip]: https://drive.google.com/open?id=0BxcdZUa_SVMcdzhLeWJuREd0UW8
[musicset_songfeatures.zip]: https://drive.google.com/open?id=0BxcdZUa_SVMcdzhLeWJuREd0UW8

## Applicability

* **Metadata Analysis**: [Collaboration profiles and their impact on musical success][SAC], ACM/SAC, Cyprus, 2019.
* **Hit Song Science**: [Causality analysis between collaboration profiles and musical success][WEB], Technical Report, Brazil, 2019.

[SAC]: https://dl.acm.org/citation.cfm?id=3297280.3297483
[WEB]: https://homepages.dcc.ufmg.br/~mirella/projs/apoena/publicacoes.html

<!-- ## Source (citation)

  ```
  @inproceedings{fma_dataset,
    title = {FMA: A Dataset for Music Analysis},
    author = {Defferrard, Micha\"el and Benzi, Kirell and Vandergheynst, Pierre and Bresson, Xavier},
    booktitle = {18th International Society for Music Information Retrieval Conference},
    year = {2017},
    url = {https://arxiv.org/abs/1612.01840},
  }
  ``` -->

## License

* The dataset is meant for research purposes.

## Acknowledgments

> The work is supported by [CNPq], Brazil.

[CNPq]: http://www.cnpq.br/