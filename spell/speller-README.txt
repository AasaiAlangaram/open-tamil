Measures of a spelling checker:
-------------------------------
Dec 12, 2017
1) Atom editor has spell check module which can be integ target.
2) Punarchi removal can be part of the setup.
3) Case conjugation rules are important to be added
4) Homebrew stemmer is also important
5) Final product can be deployed as webserver
6) Configuration for DICTIONARY/word-list is useful.

-------------------------------
0) Need language statistical data.

1) non-word error : word does not exist in dictionary:
e.g. "he lievs in the house"
         ^^^^^

2) real word error: word is in dictionary but not the right one - i.e. it could be out of context.
e.g. "he lives ink the house"
               ^^^

3) Precision - rate of correct detection
   ( 1 - Precision ) gives False alarm

4) Recall - rate of correct detection over actual number of errors

5) Errors made by system : total detection - correct detection

6) Synthetic error generation.

7) Spell checkers introduce a real-word error inplace of a detected non-word error.

8) Error model of spelling errors in Tamil (any language) is key to detect the patterns
of mistake generation, and coming with a strategy
to resolve the same.

Ref: P. Samanta, B. Chaudhari, "A simple real-word error detection and correction using local word
bigram and trigram" (2013)
