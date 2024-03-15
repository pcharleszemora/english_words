# spanish_words

A package containing the most ~5000 used Spanish words and some utility
functions. 

Spanish and English are the two most spoken languages in the United States of America.

This repo contains the most ~5000 used English words: [filiph/english_words](https://github.com/filiph/english_words). 

[This]((https://github.com/pcharleszemora/spanish_words)) repo is a fork of [that](https://github.com/filiph/english_words) repo for the purpose of containing the most ~5000 used Spanish words.
 
## Usage

Printing the top 50 most used nouns in the Spanish language:

    import 'package:spanish/spanish_words.dart';

    main() {
      nouns.take(50).forEach(print);
    }

Computing number of syllables in a word:

    syllables('beautiful');  // 3
    syllables('abatement');  // 3
    syllables('zoology');  // 4

Generating 5 interesting 2-syllable word combinations:

    generateWordPairs().take(5).forEach(print);
