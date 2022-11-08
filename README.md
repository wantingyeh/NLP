# NLP


## LemmoPoSSpacy-NLP
date: 08-11-2022
written by: Wan-Ting Yeh

### purpose of the script:
1. batch analysing text within a folder
2. using *spacy* library
3. tokenisation, lemmentisation, part-of-speech, type-token ratio

### procedure
1. Walk through all the txt files in one folder
2. steps:
  - tokenise the text
  - clean the data (Exclude unwanted token, eg., punctuation, symbols)
  - lemmentisation (talked, talking --> talk)
  - custominsed lemmentisation (eg., peeeeeekaboo --> peekaboo)
  - count unique word / total word / type-token ratio
    - unique word: only appears once in the text
    - total word: word count in the text
    - type-token ratio = unique word/ total word
  - list part of word (noun, pronoun, adj...)
3. ouput file
  - OUTPUT_PATH_final: unique word
  - OUTPUT_PATH_pos: part of speech
