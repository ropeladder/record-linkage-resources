# record-linkage-resources
Resources for tackling record linkage / deduplication / data matching / entity matching problems

_Note: If you're looking for file deduplication software, you're in the wrong place! This page focuses on deduplicating datasets._

Record linkage attempts to identify duplicate records in messy data. It is a thorny problem faced by a variety of disciplines dealing with real-world entities (most often people).

## Background

### Documents
- Wikipedia pages on [Record Linkage](https://en.wikipedia.org/wiki/Record_linkage) and [Data Deduplication](https://en.wikipedia.org/wiki/Data_deduplication)
- Overview slideshttps://www.umiacs.umd.edu/~getoor/Tutorials/ER_VLDB2012.pdf

### Talks
- Lectures by Peter Christen [1](https://www.youtube.com/watch?v=DyGonV7A_EY) [2](https://www.youtube.com/watch?v=dcNTvYDdun0) [3](https://www.youtube.com/watch?v=HAKW5tHVCmw) [4](https://www.youtube.com/watch?v=4Iv5axrAWqQ)
- Mike Mull, The Art and Science of Data Matching: https://www.youtube.com/watch?v=Y-nYEOgq3YE
- Rhydwyn Mcguire, Join for real life: https://www.youtube.com/watch?v=cEcVIjyHfiQ
- Andrew Rowe, Big Data Deduplication and Data Matching using Python: https://www.youtube.com/watch?v=Z6mlvrYEYnk

### Books
- Peter Christen, _Data Matching_: http://www.springer.com/us/book/9783642311635

## Free software
(last updated, stars)

### Python
- Dedupe: https://github.com/dedupeio/dedupe (2017, 1,413)
- RLTK: https://github.com/usc-isi-i2/rltk/ (2017, 13)
- Febrl: https://sourceforge.net/projects/febrl/ (2013)

### Java
- Duke: https://github.com/larsga/Duke (2016, 469)
- JedAI: https://github.com/scify/JedAIToolkit (2017, 12)
- LSHDB: https://github.com/dimkar121/LSHDB (2017, 9)
- FRIL: http://fril.sourceforge.net/ (2011) (Windows binary available)

### R
- RecordLinkage: https://r-forge.r-project.org/projects/recordlinkage/ https://cran.r-project.org/web/packages/RecordLinkage/index.html
- fastLink: https://github.com/kosukeimai/fastLink

### Windows Binaries
- Registry Plus™ Link Plus: https://www.cdc.gov/cancer/npcr/tools/registryplus/lp_tech_info.htm (2007)

## Commercial software and solutions
- DataMatch (by Data Ladder): https://dataladder.com/
- Reifier: http://nubetech.co/
- Dedupe: https://dedupe.io/ (freemium frontend for [Dedupe](https://github.com/dedupeio/dedupe) Python library)

## Data Cleaning

### Name Parsers

#### Python
- probablepeople: https://github.com/datamade/probablepeople (2017, 204)
python nameparser library (but purely syntax based)
- Name Parser: https://github.com/derek73/python-nameparser (2017, 232)

#### JavaScript
- parse-full-name: https://github.com/dschnelldavis/parse-full-name (2017, 18)

## Papers

## To Do
- list compatible data sources for software (CSV, SQL DB, JSON, data frame, etc...)
- list algorithms and techniques for softare (deterministic, probabalistic, graph, etc...)
- update
