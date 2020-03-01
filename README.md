# Coronvavirus (COVID-19) Academic Preprint Topic Modelling

This script does topic modelling on the latest academic pre-prints on coronavirus to see if there were any unusual patterns. Its a total experiment and I have written an article summarising the things I thought were interesting.


### Stopwords Library
Coronaviris data collected from the results section of each preprint listed in the Elsevier Novel Coronavirus Information Center accessed on March 1st 2020 - https://www.elsevier.com/connect/coronavirus-information-center

### Stopwords Library
We will need the stopwords from NLTK and spacy’s en model for text pre-processing. Later, we will be using the spacy model for lemmatization.

#### Run in python console
import nltk; nltk.download('stopwords')
#### Run in terminal or command prompt
python3 -m spacy download en

### NLP Libraries
This script requires a bunch of NLP libraries which i'm sure you will be able to download.

### Mallet Download
You will also need to download Mallet, unzip and point to that folder directory in the python script:
Download File: http://mallet.cs.umass.edu/dist/mallet-2.0.8.zip
mallet_path = '../mallet-2.0.8/bin/mallet' # update this path in the python file

### Inspiration
This script was heavily inspired by this tutorial - https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#2prerequisitesdownloadnltkstopwordsandspacymodelforlemmatization