# American English Pronunciation Dictionary

The [American English Pronunciation Dictionary](cmudict) (AmEPD) is a General
American English pronunciation dictionary.

Using John Wells' lexical sets, it has the following mergers:

 *  TRAP-BATH
 *  PALM-LOT (COT)
 *  THOUGHT-CLOTH (CAUGHT)
 *  NORTH-FORCE
 *  FLEECE-HAPPY
 *  KIT-EXPLORE

Additionally, the accent has the following mergers:

 *  HURRY-FURRY
 *  MERRY-MARRY-MARY

The context tags are defined in the `cainteoir.ttl` file of the
[pos-tags](https://github.com/rhdunn/pos-tags) project.

## History

The AmEPD is based on the CMU Pronunciation Dictionary, which has the following
history:

| Dictionary  | Version | Revision | Entries | Words   | Variants |
|-------------|---------|---------:|--------:|--------:|---------:|
| cmudict     | 0.1     |          |  99,279 |  96,151 |    3,498 |
| cmudict     | 0.2     |          | 101,717 |  98,361 |    3,735 |
| cmudict     | 0.3     |          | 110,934 | 107,400 |    3,914 |
| cmudict     | 0.4     |          | 116,253 | 111,901 |    4,885 |
| cmudict     | 0.6     |          | 127,068 | 120,031 |    7,672 |
| cmudict     | 0.6d    |     7825 | 129,482 | 120,280 |   10,039 |
| cmudict     | 0.6e    |     7825 | 133,751 | 124,272 |   10,329 |
| cmudict     | 0.7a    |    12245 | 133,334 | 123,698 |    9,636 |
| cmudict     | 0.7b    |    13090 | 134,373 | 125,770 |    8,603 |
| cmudict-new | 0.7b    |    13246 | 135,009 | 125,929 |    9,080 |

Version 0.5 was not released publically.

Version 0.6e is a reconstruction of the unreleased 0.7 version, created by Alex
I. Rudnicky, as described by the `README.old` file in the `cmusphinx` repository.
This is the basis for the 0.1 release of AmEPD.

The 0.2 version of AmEPD incorporates the pronunciation fixes and additions from
cmudict 0.7a, cmudict 0.7b and cmudict-new.

The AmEPD has the following history:

| Dictionary  | Version | Revision | Entries | Words   | Variants | Parts of Speech |
|-------------|---------|---------:|--------:|--------:|---------:|----------------:|
| amepd       | 0.1     |     7825 | 128,627 | 121,958 |    5,970 |           1,252 |
| amepd       | master  |    13246 | 129,064 | 124,265 |    4,070 |           1,304 |

The `Revision` column refers to the commit in the
[cmusphinx](https://sourceforge.net/p/cmusphinx/code/HEAD/tree/)
subversion repository where that version of the dictionary originates.

## License

Copyright (C) 1993-2015 Carnegie Mellon University. All rights reserved.  
Copyright (C) 2016-2017 Reece H. Dunn (Cainteoir Technologies). All rights reserved.

The American English Pronunciation Dictionary is released under a
[2-clause BSD](COPYING) license.
