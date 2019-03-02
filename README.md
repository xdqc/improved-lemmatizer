# Lemmatizer

## Improved lemmatizer based on nltk.stem.WordNetLemmatizer working on any part of speech

Tested with top 100,000 most frequent words in the cocktail corpus of COCA, Google N-gram, Open Subtitle, Wikipedia.

## Usage

Install NLTK https://www.nltk.org/install.html

```python
 >>> from Lemmatizer import lemmatize

 >>> lemmatize('us')
 us
 # WordNetLemmatizer returns 'u'

 >>> lemmatize('as')
 as
 # WordNetLemmatizer returns 'u'

 >>> lemmatize('rating')
 rate
 # WordNetLemmatizer returns 'rat'

 >>> lemmatize('wages')
 wage
 # WordNetLemmatizer returns 'wag'

 >>> lemmatize('passed')
 pass
 # WordNetLemmatizer returns 'pas'

 >>> lemmatize('assesses')
 assess
 # WordNetLemmatizer returns 'ass'

 >>> lemmatize('feed')
 feed
 # WordNetLemmatizer returns 'fe'

 >>> lemmatize('bees')
 bee
 # WordNetLemmatizer returns 'be'

 >>> lemmatize('axes')
 axe
 # WordNetLemmatizer returns 'ax'
```
