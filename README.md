# Record Linkage Resources
Resources for tackling record linkage (also known as deduplication, data matching, entity resolution)

_Note: If you're looking for file deduplication software, you're in the wrong place! This page focuses on deduplicating datasets._

_Also note: Nor is this page is not about deduplication software used in backup and storage._

Record linkage attempts to identify duplicate records in messy data. It is a thorny problem that crops up in a variety of scenarios that attempt to understand with real-world entities (most often people), such as census and statistical bureaus, medical organizations, the social sciences, and of course commercial business.

For example, are these records the same person? Record Linkage is how you make the computer decide--quickly.

| Name | Address | Phone |
| --- | --- | --- |
| Bill Smith | 123 N. Main St. | 555-1235 |
| Smith, William K. | 123 Main | - |
| W. K. Smith | North Main Street | 222-555-1234 |
| Bill Schmidt | 1230 Main St. | 542-1235 |

## Background

### Documents
- Wikipedia pages on [Record Linkage](https://en.wikipedia.org/wiki/Record_linkage) and [Data Deduplication](https://en.wikipedia.org/wiki/Data_deduplication)
- Overview slides: https://www.umiacs.umd.edu/~getoor/Tutorials/ER_VLDB2012.pdf
- [Dedupe](https://github.com/dedupeio/dedupe)'s explanation of how their software works: https://dedupe.io/developers/library/en/latest/How-it-works.html

### Talks
- Peter Christen, Record Linkage lectures at ADRC-Scotland: [1](https://www.youtube.com/watch?v=DyGonV7A_EY) [2](https://www.youtube.com/watch?v=dcNTvYDdun0) [3](https://www.youtube.com/watch?v=HAKW5tHVCmw) [4](https://www.youtube.com/watch?v=4Iv5axrAWqQ) (2015)
- Mike Mull, The Art and Science of Data Matching: https://www.youtube.com/watch?v=Y-nYEOgq3YE (2015)
- Rhydwyn Mcguire, Join for real life: https://www.youtube.com/watch?v=cEcVIjyHfiQ (2013)
- Andrew Rowe, Big Data Deduplication and Data Matching using Python: https://www.youtube.com/watch?v=Z6mlvrYEYnk (2013)

### Books
- Peter Christen, _Data Matching_: http://www.springer.com/us/book/9783642311635
- Thomas N. Herzog, Fritz J. Scheuren and William E. Winkler, _Data Quality and Record Linkage Techniques_: http://www.springer.com/us/book/9780387695020

## Free software
(last updated, stars)

### Python
- Dedupe: https://github.com/dedupeio/dedupe (2017, 1,413)
- Python Record Linkage Toolkit: https://github.com/J535D165/recordlinkage (2017, 92)
- RLTK: https://github.com/usc-isi-i2/rltk/ (2017, 13)
- Febrl: https://sourceforge.net/projects/febrl/ (2013)
- ebLink for Python: https://github.com/aldengolab/graphical-record-linkage (2016, 4) (Python wrapper for ebLink)
- anonlink: anonymous linkage using cryptographic linkage keys https://github.com/n1analytics/anonlink (2018, 3)

### Java
- Duke: https://github.com/larsga/Duke (2016, 469)
- JedAI: https://github.com/scify/JedAIToolkit (2017, 12)
- LSHDB: https://github.com/dimkar121/LSHDB (2017, 9)
- FRIL: http://fril.sourceforge.net/ (2011) (Windows binary available)

### R
- RecordLinkage: https://r-forge.r-project.org/projects/recordlinkage/ https://cran.r-project.org/web/packages/RecordLinkage/index.html
- fastLink: https://github.com/kosukeimai/fastLink (2017, 47)
- ebLink: https://github.com/resteorts/ebLink (2016, 6)

### Other
- OpenRecLink: http://reclink.sourceforge.net/ (2016)
  - C++ with GUI
- Registry Plus™ Link Plus: https://www.cdc.gov/cancer/npcr/tools/registryplus/lp_tech_info.htm (2007)

## Commercial software and solutions
- Data Ladder DataMatch: https://dataladder.com/
- Dedupe: https://dedupe.io/ (freemium frontend for [Dedupe](https://github.com/dedupeio/dedupe) Python library)
- LinkageWiz: http://www.linkagewiz.net/
- WinPure Clean and Match: http://www.winpure.com/cleanmatch.html
- Reifier: http://nubetech.co/

### For SAS
- (free but requires SAS) The Link King: http://www.the-link-king.com/

## Data Cleaning

### Name Parsers

#### Python
- probablepeople: https://github.com/datamade/probablepeople (2017, 204)
python nameparser library (but purely syntax based)
- Name Parser: https://github.com/derek73/python-nameparser (2017, 232)

#### JavaScript
- parse-full-name: https://github.com/dschnelldavis/parse-full-name (2017, 18)

## Papers
- US Census Bureau Data Linkage research: https://www.census.gov/srd/csrm/RecordLinkage.html
- [Learnable Similarity Functions and their Application to Record Linkage and Clustering](http://www.cs.utexas.edu/%7Eml/papers/marlin-dissertation-06.pdf) ([via](https://github.com/dedupeio/dedupe))
- [https://www.microsoft.com/en-us/research/publication/improving-entity-resolution-with-global-constraints/ ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- https://arxiv.org/abs/1312.4645 ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- http://people.cs.umass.edu/~mwick/MikeWeb/Publications_files/wick09entity.pdf ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- http://homes.cs.washington.edu/~pedrod/papers/mrdm04.pdf ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- https://www.researchgate.net/publication/318874102_Clink_-_A_Novel_Record_Linkage_Methodology_based_on_Graph_Interactions

## Organizations
- US Census Burea - Center for Statistical Research and Methodolgy - Record Linkage: https://www.census.gov/srd/csrm/RecordLinkage.html
- Stanford Entity Resolution Framework: http://infolab.stanford.edu/serf/
- ANU Data Mining and Matching Group https://dmm.anu.edu.au/ https://web.archive.org/web/20160515215747/datamining.anu.edu.au/projects/linkage.html (Archive.org link)

## Misc
- DuDe (framework for comparing record linkage results): https://hpi.de/naumann/projects/data-quality-and-cleansing/dude-duplicate-detection.html
- Datasets to use for evaluating deduplication software: https://hpi.de/naumann/projects/repeatability/datasets.html
- https://www2.vrdc.cornell.edu/news/3/20050420-Record%20Linkage%20Software.pdf

## To Do
- list compatible data sources for software (CSV, SQL DB, JSON, data frame, etc...)
- GUI or not?
- list algorithms and techniques for softare (deterministic, probabalistic, graph, etc...)

Suggestions / contributions welcome! I am not an expert on record linkage, this is simply a list of things I've found when working on a difficult deduplication problem for [Thicket.io](https://thicket.io).
