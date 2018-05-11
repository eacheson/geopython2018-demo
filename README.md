# GeoPython 2018 lightning talk
Demo presented at the [GeoPython 2018](http://2018.geopython.net/) conference as a lightning talk.

To run this notebook you'll have to minimally:
- install the python libraries imported at the top of the notebook (conda and some via pip)
- download the [Stanford Named Entity Recognizer (NER)](https://nlp.stanford.edu/software/CRF-NER.shtml); I use v3.8.0 which you can [download here](https://nlp.stanford.edu/software/stanford-ner-2017-06-09.zip), unzip, then adjust the `CLASSPATH` and `STANFORD_MODELS` os.environ paths at the top of the notebook
- use nltk.download() to download nltk models
- set a data path for `nltk` if you get a `LookupError` from nltk below even after downloading relevant models (also at top of notebook)
