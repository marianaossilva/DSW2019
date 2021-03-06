<img src="icon.png" align="right" />

# DSW 2019 - DATASET SHOWCASE WORKSHOP ![GitHub repo size](https://img.shields.io/github/repo-size/marianaossilva/DSW2019.svg?color=d43f3a)

[MusicOSet]: https://marianaossilva.github.io/DSW2019

> [MusicOSet][MusicOSet] - An Enhanced Music Dataset for Music Data Mining

## Dataset Information

This repository stores an open and enhanced dataset of musical elements (music, albums, and artists) suitable for music data mining. 

The attractive features of [MusicOSet][MusicOSet] include:
* Integration and centralization of different musical data sources
* Calculation of popularity scores and classification of hits and non-hits musical elements, varying from 1962 to 2018
* Enriched metadata for music, artists, and albums from the US popular music industry
* Availability of acoustic and lyrical resources
* Unrestricted access in two formats: SQL database and compressed .csv files

## Dataset Statistics

---
**Data** | **# Records**
--- | ---
Songs | 20,405
Artists | 11,518
Albums | 26,522
Lyrics | 19,664
Acoustic Features | 20,405
Genres | 1,561
---

## Schema

<img src="docs/assets/img/schema.svg" align="right" />

## Format and Usage

[MusicOSet][MusicOSet] is available in a public repository in two different formats

1. **Relational Database** 
	- **[musicoset.sql]**:  SQL file that will create the relational database and subsequently loads all the information in the tables by a MySQL installation (233MB) 
2. **.csv Tables**
	- **[musicoset_metadata.zip]**: Contains textual and numeric information about songs, artists, and albums (5,73MB)
	- **[musicoset_popularity.zip]**: Contains nine tables of musical popularity information (11,8MB)
	- **[musicoset_songfeatures.zip]**: Contains lyrics and acoustic fingerprints of the songs collected (52MB)

[musicoset.sql]: https://drive.google.com/open?id=1PXmpTLuDA40Ox8uHM7R2-s7UYH4hwbzx
[musicoset_metadata.zip]: https://github.com/marianaossilva/DSW2019/blob/master/docs/assets/data/musicoset_metadata.zip
[musicoset_popularity.zip]: https://github.com/marianaossilva/DSW2019/blob/master/docs/assets/data/musicoset_popularity.zip
[musicoset_songfeatures.zip]: https://github.com/marianaossilva/DSW2019/blob/master/docs/assets/data/musicoset_songfeatures.zip

## Applicability

* **Metadata Analysis**: [Collaboration profiles and their impact on musical success][SAC], ACM/SAC, Cyprus, 2019.
* **Hit Song Science**: [Causality analysis between collaboration profiles and musical success][WEB], Technical Report, Brazil, 2019.

[SAC]: https://dl.acm.org/citation.cfm?id=3297280.3297483
[WEB]: https://homepages.dcc.ufmg.br/~mirella/projs/bade/

## Source (citation)

  ```
  @InProceedings{silva2019musicoset,
  title     = {{MusicOSet: An Enhanced Open Dataset for Music Data Mining}},
  author    = {Silva, Mariana O. and Rocha, La\'{\i}s M. and Moro, Mirella M.},
  booktitle = {{XXXIV} Simp{\'{o}}sio Brasileiro de Banco de Dados: Dataset Showcase Workshop, {SBBD} 2019 Companion},
  address   = {Fortaleza, CE, Brazil},
  year      = {2019}
  }
  ```

## License

* The dataset is meant for research purposes.

## Acknowledgments

> The work is supported by [CNPq], Brazil.

[CNPq]: http://www.cnpq.br/