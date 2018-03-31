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

Additionally, the accent has the following mergers at syllable boundaries
before `/R/`:

 *  HURRY-FURRY
 *  MERRY-MARRY-MARY
 *  MIRROR-NEARER

The context tags are defined in the `cainteoir.ttl` file of the
[pos-tags](https://github.com/rhdunn/pos-tags) project.

## History

The `Revision` column in the tables below refers to the commit id of that
version of the CMU pronunciation dictionary. Versions without a revision
are available from the
[comp.speech](ftp://svr-ftp.eng.cam.ac.uk/pub/comp.speech/dictionaries/cmudict/)
FTP server. From cmudict 0.6d, `Revision` refers to the
[cmusphinx](https://sourceforge.net/p/cmusphinx/code/HEAD/tree/)
subversion repository commit id.

### amepd

| Version | Date       | Revision | Entries | Words   | Variants | Parts of Speech |
|---------|------------|---------:|--------:|--------:|---------:|----------------:|
| 0.0     | 2016-03-18 |     7825 | 131,920 | 121,883 |   10,037 |               0 |
| 0.1     | 2016-04-14 |     7825 | 128,627 | 121,958 |    5,970 |           1,252 |
| 0.2     | 2017-07-15 |    13090 | 129,064 | 124,265 |    4,070 |           1,304 |
| master  | 2018-03-30 |    13090 | 128,945 | 124,282 |    3,934 |           1,304 |

Version 0.0 is based on cmudict 0.6e with the following entries removed:
spelling-based entries, entries with non-letter characters, and hyphenated
entries.

Version 0.2 incorporates the pronunciation fixes and additions from cmudict
0.7a, cmudict 0.7b, and cmudict-new.

### cmudict-new

| Commit   | Date       | AmEPD | Entries | Words   | Variants |
|---------:|------------|-------|--------:|--------:|---------:|
| 132be0d6 | 2016-09-29 | 0.2   | 135,009 | 125,929 |    9,080 |

The `cmudict-new` dictionary is being maintained in the
[cmusphinx/cmudict](https://github.com/cmusphinx/cmudict) GitHub repository.

The `AmEPD` column is the version of AmEPD that incorporates the specified
version of cmudict-new.

### cmudict

| Version | Date       | Revision | Entries | Words   | Variants |
|---------|------------|---------:|--------:|--------:|---------:|
| 0.1     | 1993-09-15 |          |  99,279 |  96,151 |    3,498 |
| 0.2     | 1994-03-09 |          | 101,717 |  98,361 |    3,735 |
| 0.3     | 1994-09-27 |          | 110,934 | 107,400 |    3,914 |
| 0.4     | 1995-11-07 |          | 116,253 | 111,901 |    4,885 |
| 0.6     | 1998-10-19 |          | 127,068 | 120,031 |    7,672 |
| 0.6d    | 2008-02-19 |     7825 | 129,482 | 120,280 |   10,039 |
| 0.6e    | 2008-02-19 |     7825 | 133,751 | 124,272 |   10,329 |
| 0.7a    | 2014-02-17 |    12245 | 133,334 | 123,698 |    9,636 |
| 0.7b    | 2015-07-30 |    13090 | 134,373 | 125,770 |    8,603 |

Version 0.5 was not released publically.

Version 0.6e is a reconstruction of the unreleased 0.7 version, created by Alex
I. Rudnicky, as described by the `README.old` file in the `cmusphinx` repository.
This version is not officially released as 0.6e. It is from the 0.7a dictionary
in the first revision of cmudict in the cmusphinx repository, which is used as
the base of the 0.7a release.

## License

Copyright (C) 1993-2015 Carnegie Mellon University. All rights reserved.  
Copyright (C) 2016-2018 Reece H. Dunn (Cainteoir Technologies). All rights reserved.

The American English Pronunciation Dictionary is released under a
[2-clause BSD](COPYING) license.
