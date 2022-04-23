# German Climate Change Tweet Corpus (GerCCT)

This is the repo of the GerCCT Corpus, a German tweet resource annotated for argument components, argument properties, sarcasm and toxic language. 

## About

The corpus consists of 1,200 tweets and its annotations. Each tweet is associated with its respective source tweet, i.e. the tweet it replies to. Source tweets were used to provide annotators with additional context. The annotations refer to the reply tweet, i.e. NOT to the source tweet. For copyright reasons we cannot distribute the actual tweet content. Instead we share the source and reply tweet IDs and the annotations. 

The current version includes class annotations on the document level, i.e. on the tweet level. We are working on creating the respective span annotations. 

## Basic Corpus Statistics

### Corpus Size

Unit | Min Per Tweet | Max Per Tweet | Mean Per Tweet | Total
-----|---------------|---------------|----------------|------
Word Tokens | 1 | 62 | 32 | 38,350
Sentences | 1 | 8 | 2 | 2,850

### Class Distribution 

#### Argument Components

Class | Absolute # | Proportion 
------|------------|-----------
Argument | 844 | 0.70
Claim | 784 | 0.65 
Evidence | 295 | 0.25

#### Argument Properties

Class | Absolute # | Proportion
------|------------|-----------
Unverifiable Claim | 703 | 0.59
Verifiable Claim | 244 | 0.20
Reason | 132 | 0.11
External Evidence | 165 | 0.14 
Internal Evidence | 11 | 0.01

#### Sarcasm and Toxic Language

Class | Absolute # | Proportion
------|------------|-----------
Sarcasm | 204 | 0.17
Toxic Language | 173 | 0.14

## Citation

The accompanying paper was accepted to be published at LREC 2022.

## License

CC-BY-SA-4.0