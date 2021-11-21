---
title: "Australian corpus preparation"
date: 2021-11-21
tags: "analysis"
---

<p align="center">
<img src="https://daryavanichkina.com/images/2111_corpus.jpg" width="500" />
</p>

Photo by <a href="https://unsplash.com/@ugur?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ugur Akdemir</a> on <a href="https://unsplash.com/s/photos/corpus?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

## Clients

- [Prof Monika Bednarek](https://www.sydney.edu.au/arts/about/our-people/academic-staff/monika-bednarek.html), Faculty of Arts & Social Sciences, University of Sydney

## Purpose

- The clients prepared a corpus of media articles around a specific topic (*confidential*).
- The corpus was manually downloaded from LexisNexis on Windows. 
- Multiple character encoding issues were encountered as a result of this, which made it incompatible with tools the clients wanted to use.
- The aim was to generate a "clean" corpus that could be used for data analysis.

## Approach

- Resolved encoding issues in the 27 000+ articles from 12 Australian newspapers.
- Implemented near-duplicate detection, visualisation and removal using minhash and locality-sensitive hashing ("reimplemented Turnitin in Python") to ensure subsequent statistical analyses were not invalid due to duplicates.
- Used topic modelling to create sub-corpora for further analysis.
- Translated analytics spreadsheets used by researchers to a standalone Python script, automating and scaling one-vs-all and one-vs-one sub-corpus analysis.
- Provided comprehensive client-interpretable documentation.

## Key tools

- *Key tools: Python: pandas, chardet, spacy, seaborn, gensim, datasketch; Git + GitHub; Jira; fdupes*.
