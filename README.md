# Novelty Detection in scientific research papers

NLP Final Year Project for finding novelty in scientific research papers.
Project website link: https://namiyousef.github.io/novelty_detection/
This is a personal GitHub repository that includes a summarised results and snippets of code. For the entire work flow please visit https://github.com/lsalles23/ContentMining.
The repository is private, so please contact me at namiyousef@hotmail.com for access.
![TurbomachineryWordCloud](https://github.com/namiyousef/novelty_detection/docs/img/brochure_pip_HD.png)
# Executive Summary

Determining whether a document contains novel research or not simplifies the otherwise laborious literature review process. This is a largely unsolved problem, both due to the difficulty in defining what constitutes novel research and in extracting document level semantic relationships using statistical methods. In recent years, Deep Learning has boosted Natural Language Processing (NLP), particularly deep representations of text. Despite this, there has been little research into using NLP to detect the novelty of long documents (e.g. scholarly articles).
This paper defines novelty as dissimilarity provided that the document is relevant. Two novelty detection models (pseudo-supervised and unsupervised) are introduced to address this issue. The former, based on a pairwise convolutional neural network, is computationally and memory intensive. It was unable to train. The unsupervised model is based on outlier detection in an embedding space. The model was found to perform well for pre-processing tasks (i.e. filtering out irrelevant documents) but not for novelty detection.
Future researchers are encouraged to find representative document embeddings, including graph based representations.