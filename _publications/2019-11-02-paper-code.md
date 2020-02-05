---
title: "Code-Switched Language Models Using Neural Based Synthetic Data from Parallel Sentences"
collection: publications
status: published
permalink: /publication/2019-11-02-paper-code
excerpt: ''
date: 2019-11-02
venue: 'CoNLL'
paperurl: ''
authors: 'Genta Indra Winata, Andrea Madotto, Chien-Sheng Wu, Pascale Fung'
citation: ''
paper: 'https://www.aclweb.org/anthology/K19-1026.pdf'
---
Training code-switched language models is difficult due to lack of data and complexity in the grammatical structure. Linguistic constraint theories have been used to generate artificial code-switching sentences for decades to cope with this issue. However, this require external word alignments or constituency parsers that create erroneous results on distant languages. We propose a sequence-to-sequence model using a copy mechanism to generate code-switching data by leveraging parallel monolingual translations from a limited source of code-switching data. The model learns how to combine words from parallel sentences and identifies when to switch one language to the other. Moreover, it captures code-switching constraints by attending and aligning the words in inputs, without requiring any external knowledge. Based on experimental results, the language model trained with the generated sentences achieves state-of-the-art performance and improves end-to-end automatic speech recognition.