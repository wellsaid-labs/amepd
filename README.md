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
version of the dictionary. Versions without a revision are available from the
[comp.speech](ftp://svr-ftp.eng.cam.ac.uk/pub/comp.speech/dictionaries/cmudict/)
FTP server. From cmudict 0.6d, `Revision` refers to the
[cmusphinx](https://sourceforge.net/p/cmusphinx/code/HEAD/tree/)
subversion repository commit id.

The `cmudict-new` dictionary is being maintained in the
[cmusphinx/cmudict](https://github.com/cmusphinx/cmudict) GitHub repository.
The `Revision` column for this dictionary is the SHA1 commit id from that
repository shortened to 8 characters.

### amepd

| Dictionary  | Version | Revision | Entries | Words   | Variants | Parts of Speech |
|-------------|---------|---------:|--------:|--------:|---------:|----------------:|
| amepd       | 0.0     |     7825 | 131,920 | 121,883 |   10,037 |               0 |
| amepd       | 0.1     |     7825 | 128,627 | 121,958 |    5,970 |           1,252 |
| amepd       | 0.2     |    13246 | 129,064 | 124,265 |    4,070 |           1,304 |
| amepd       | master  |    13246 | 128,945 | 124,282 |    3,934 |           1,304 |

Version 0.0 is based on cmudict 0.6e with the following entries removed:
spelling-based entries, entries with non-letter characters, and hyphenated
entries.

Version 0.2 incorporates the pronunciation fixes and additions from cmudict
0.7a, cmudict 0.7b, and cmudict-new.

### cmudict and cmudict-new

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
| cmudict-new | 0.7b    | 132be0d6 | 135,009 | 125,929 |    9,080 |

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
