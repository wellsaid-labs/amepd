# Change Log

### 0.2 - 2017-07-15

*  Renamed the `context` annotations to `usage`.
*  Relicensed to the 2-clause BSD license, like cmudict 0.7a.
*  Incorporated the cmudict 0.7a (cmusphinx revision 12245) changes into the
   dictionary.
*  Incorporated the cmudict 0.7b (cmusphinx revision 13090) changes into the
   dictionary, excluding the `AH0` to `AA0` changes and the stressing of
   terminal `AH`, `AA`, `OW` and `IY` vowels.
*  Incorporated the cmudict-new (cmusphinx revision 13246) changes into the
   dictionary.
*  Reduced the number of pronunciation variants in the dictionary.
*  Many pronunciation fixes and additions.

New Words:

*  Arthur Conan Doyle - The Adventure of the Bruce-Partington Plans \[1912\] (Project Gutenberg eText 2346)
*  Edgar Allan Poe - The Cask of Amontillado \[1846\] (Project Gutenberg eText 1063)
*  Edgar Allan Poe - The Masque of the Red Death \[1842\] (Project Gutenberg eText 1064)
*  Edgar Allan Poe - The Oval Portrait \[1842\] (Project Gutenberg eText 2147)
*  Edgar Allan Poe - The Raven \[1845\] (Project Gutenberg eText 1065)
*  William Shakespeare - The Phoenix and the Turtle \[1601\] (Project Gutenberg eText 1525)

### 0.1-1 - 2016-04-23

*  Fix dictionary validation errors from the `cmudict-tools` program.
*  Use the `cainteoir` part-of-speech SKOS vocabulary for context entries.

### 0.1 - 2016-04-14

*  Based on cmudict 0.7 (cmusphinx revision 7825).
*  Removed hyphenated entries.
*  Removed entries with symbol and number characters.
*  Removed abbreviations (spelling based entries).
*  Use `AX` instead of `AH0` for `COMMA` vowels (`STRUT`-`COMMA` split).
*  Use `AXR` instead of `ER0` for `LETTER` vowels (`NURSE`-`LETTER` split).
*  Add part of speech and `context` annotations for words with different
   pronunciations.
*  Reduced the number of pronunciation variants in the dictionary.
*  Many pronunciation fixes.
