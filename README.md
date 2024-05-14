# NDS_Metrics-Score-

# Objective
* Using data [News Dataset BBC](https://www.kaggle.com/datasets/gpreda/bbc-news) from 2013 to 2024. 
* Comparing (similiarity) two NDS  with metrics.
* Find higher scoring queries that are most similar to news headlines.

# Scope
* Techique embedding data  with TFIDF and Counvectorizer( Bag of word )
* Find query beetween NDS to find higher similiarity

# How to use
<pre>
pip venv "you name venv"
pip install requirements.txt
</pre>

# Result
## Cosine Similiarity with TFIDF Embedding
|                                                        |   health ukranian |
|:-------------------------------------------------------|------------------:|
| Cold weather: How do cold-health alerts work?          |          0.487961 |
| Matt Hancock paid £320K for I'm a Celebrity appearance |          0.318486 |
| England appoints ambassador to shake up women's health |          0.309159 |
| Head teacher apologises after pupils hurt in crush     |          0.3019   |
| Strep A symptoms: What you need to know, in a minute   |          0.301159 |

## Cosine Similiarity with Bag Of word Embedding
|                                                                |   health ukranian |
|:---------------------------------------------------------------|------------------:|
| Cold weather: How do cold-health alerts work?                  |          0.5547   |
| New treatment for migraine attacks on NHS to benefit thousands |          0.377964 |
| What is GDP and how does it affect me?                         |          0.377964 |
| Head teacher apologises after pupils hurt in crush             |          0.353553 |
| Strep A symptoms: What you need to know, in a minute           |          0.353553 |

## Comparing 
Higher score similiarity query ```health ukranian``` using embedding Bag of word or in scikit-learn Counvectorizer



