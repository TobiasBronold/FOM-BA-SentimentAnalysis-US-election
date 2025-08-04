# Sentiment Analysis for the US presidental election

This repository contains the customized code from my bachelor thesis at the FOM University in Munich. It deals with an evaluation of sentiment towards the 2016, 2020 and 2024 US presidential election cycles using Transformer models.

This repository contains the customized code from my bachelor thesis at the FOM University in Munich. It deals with an evaluation of sentiment towards the 2016, 2020 and 2024 US presidential election cycles using Transformer models.

The procedure can be adapted to different areas. The rough procedure is as follows:
1. extract YouTube comments with the API
2. preparatory labeling with VADER and manual correction of incorrectly set labels 
3. training various transformer models (e.g. BERT, DistilBERT, RoBERTa) on the labeled data
4. inference of the best model on the remaining data. 
5. graphical evaluation

## Requirements
