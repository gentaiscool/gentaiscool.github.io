---
title: "Coach: A Coarse-to-Fine Approach for Cross-domain Slot Filling"
collection: publications
status: published
permalink: /publication/2020-07-07-paper-coach
excerpt: ''
date: 2020-07-07
venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2004.11727.pdf'
authors: 'Zihan Liu, Genta Indra Winata, Peng Xu, Pascale Fung'
citation: ''
code: 'https://github.com/zliucr/coach'
paper: 'https://arxiv.org/pdf/2004.11727.pdf'
---
As an essential task in task-oriented dialog systems, slot filling requires extensive training data in a certain domain. However, such data are not always available. Hence, cross-domain slot filling has naturally arisen to cope with this data scarcity problem. In this paper, we propose a Coarse-to-fine approach (Coach) for cross-domain slot filling. Our model first learns the general pattern of slot entities by detecting whether the tokens are slot entities or not. It then predicts the specific types for the slot entities. In addition, we propose a template regularization approach to improve the adaptation robustness by regularizing the representation of utterances based on utterance templates. Experimental results show that our model significantly outperforms state-of-the-art approaches in slot filling. Furthermore, our model can also be applied to the cross-domain named entity recognition task, and it achieves better adaptation performance than other existing baselines. The code is available at this https://github.com/zliucr/coach. 

[Paper](https://arxiv.org/pdf/2004.11727.pdf)