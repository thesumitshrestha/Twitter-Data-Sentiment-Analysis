# Twitter-Data-Sentiment-Analysis

Derives sentiment from the text data by using text mining and NLP methods.
## 
```diff
 Objective: Perform Sentiment Analysis on Twitter data by using NLP techniques, NLTK and Scikit-Learn library.
```

### Roadmap
<img src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/roadmap.png' alt='RoadMap'/>


### WordCloud
Generated WordCloud of Positive(left) and Negative(right) tweets to get a quick overview of the most recurrent words in the text corpus.


<img width='40%' align='left' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/word-cloud-positive.png' alt='Word Cloud Positive' title='test'/>
<img width='40%' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/word-cloud-negative.png' alt='Word Cloud Negative'/>

## Text Normalization
For reducing randomness in a particular piece of the text.
e.g. from Learning NLP is fun -> learn nlp fun

### Text Cleaning
Removed all items which doesn't provide additional information by using Regex, Letter repetition, Capitalization and Contradicton like won't -> will not.

### Tokenization
Separted into small chunks after removing Punctuations, Stop Words and Number.

### Stemming
Reduced the words to their root form.
e.g. manager, management, managing -> manag

### Lemmatization
Reduced the words to their root form with the use of word context using Part of Speech(POS)
e.g. running(noun), running(adj), running(verb) -> run

## Text Vectorization / Text Representation
Used three different approaches - Positive/Negative Frequencies, Bag of Words and TF-IDF using scikit-learn library.

## Machine Learning Model
### Model Training
Used 80% dataset and trained them using scikit-learn library

### Logistic Regression
Used logistic regression for model fitting in the training dataset (t= βo+β1x1+β2x2+ ......+βnxn).

## Performance Metrics
### Accuracy Measure
### Positive/Negative Frequencies LR Model
<img width='30%' align='center' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/accuracy-positive-negative.png' alt='Accuracy'/>

#### Bag of Models LR Model
<img width='30%' align='center' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/accuracy-bag-of-words.png' alt='Accuracy'/>

#### TF-IDF LR Model
<img width='30%' align='center' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/accuracy-tf-idf.png' alt='Accuracy'/>

### Confusion Matrix

#### For Positive/Negative Frequencies LR Model
<img width='40%' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/positive-negative.png' alt='Bag of Words'/>

#### For Bag of Models LR Model
<img width='40%' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/bag-of-words.png' alt='Bag of Words'/>

#### For TF-IDF LR Model
<img width='40%' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/tf-idf.png' alt='Bag of Words'/>


## Output
<img width='40%' src='https://raw.github.com/thesumitshrestha/Twitter-Data-Sentiment-Analysis/main/images/output.png' alt='Output'/>

```diff
Conclusion: TF-IDF and Bag of Models seems to more accurate than Positive/Negative Frequencies.
```
