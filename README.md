# Improved lemmatizer on top WordNetLemmatizer 

`nltk.stem.WordNetLemmatizer` is (one of?) the best lemmatizer, and it can be better.

Tested with top 100,000 most frequent words in the [cocktail corpus](https://github.com/xdqc/english-corpus-words-frequency) of COCA (45%), Google Ngram (40%), Wikipedia (8%), Open Subtitle (4%) and Twitter (3%).

## Usage

Install NLTK https://www.nltk.org/install.html

```python
 >>> from Lemmatizer import lemmatize

 >>> lemmatize('us')
 us
 # WordNetLemmatizer returns 'u'

 >>> lemmatize('as')
 as
 # WordNetLemmatizer returns 'a'

 >>> lemmatize('during')
 during
 # WordNetLemmatizer returns 'dur'

 >>> lemmatize('rating')
 rate
 # WordNetLemmatizer returns 'rat'

 >>> lemmatize('wares')
 ware
 # WordNetLemmatizer returns 'war'

 >>> lemmatize('obsessing')
 obsess
 # WordNetLemmatizer returns 'ob'

 >>> lemmatize('assesses')
 assess
 # WordNetLemmatizer returns 'ass'

 >>> lemmatize('abysses')
 abyss
 # WordNetLemmatizer returns 'ab'

 >>> lemmatize('feed')
 feed
 # WordNetLemmatizer returns 'fee'

 >>> lemmatize('ground')
 ground
 # WordNetLemmatizer returns 'grind'

 >>> lemmatize('bees')
 bee
 # WordNetLemmatizer returns 'be'

 >>> lemmatize('axes')
 axe
 # WordNetLemmatizer returns 'ax'
```
