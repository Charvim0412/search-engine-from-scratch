# Search Engine From Scratch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Charvim0412/search-engine-from-scratch/blob/main/search_engine.ipynb)

An inverted-index search engine built with only the Python standard library
(plus a stemmer), tested on the 20 Newsgroups dataset (~18k documents).

## Features
- Tokenizer with stop-word removal and Porter stemming
- Inverted index with word positions
- Boolean search (AND / OR / NOT, parentheses) using sorted-list merging
- Ranked search with TF-IDF and BM25
- Benchmark comparing the index against a naive scan
- Interactive search box demo

## How to run
Click the "Open in Colab" badge above, then choose Runtime → Run all.

## Results
![Benchmark](benchmark.png)
