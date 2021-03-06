# NLP in Python and ElasticSearch

Conference talk materials for the Dato/Turi data science symposium in SF, July 12-13, 2016.
Online slides to go with: http://ghostweather.slides.com/lynncherny/deck-6.

This talk is really a long tutorial -- how to go from a giant mess of data to a search app on the web.  The ES api is a little tricky and there aren't a lot of good end-to-end tutorials and use cases out there.  If you are Python fluent, this will get you to the web.

Three parts:

* 1. Mostly pandas exploratory analysis of Yelp  eviews in Python, and some simple NLP.  Create dataframes that can be read into Elasticsearch.  Simple sentiment by dictionary.  Trends over time, and other exploration including aggregations by user and business. This is the **["1. Yelp Reviews Explored in Python"](https://github.com/arnicas/nlp_elasticsearch_reviews/blob/master/1.%20Yelp%20Reviews%20Explored%20in%20Python.ipynb)** notebook.
* 2. Elasticsearch demo and examples in another notebook, using saved df's, in **["2. ElasticSearch-Tricks-and-Tips.ipynb"](https://github.com/arnicas/nlp_elasticsearch_reviews/blob/master/2.%20ElasticSearch-Tricks-and-Tips.ipynb)**.  This file explores how you will set up your own ES indexing, custom analyzers in ES, non-trivial queries, etc.
* 3. Web demo using the elasticsearch-js library, in the [web directory](https://github.com/arnicas/nlp_elasticsearch_reviews/tree/master/web).  Assumes a running localhost instance of your indexed data.

All of them assume localhost usage.

### Python Environment

Install and use miniconda from Continuum. Create your environment with:

```` 
conda env create -f environment.yml
[.... say yes to everything...]
source activate esnlp
````

It's called "esnlp".

### Slides

Again: online slides to go with: http://ghostweather.slides.com/lynncherny/deck-6.

I'm @arnicas on Twitter.

