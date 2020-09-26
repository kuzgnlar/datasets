<img src="header_background.jpg" height ="38%" width="38%"></img> 

# Kuzgunlar Turkish Datasets

![GPL 3.0](https://img.shields.io/badge/license-GPLv3-red.svg)

## NER
  The dataset of [Kuzgunlar Turkish Electra NER Model](https://huggingface.co/kuzgunlar/electra-turkish-ner)
  
> Sahin, H. Bahadir; Eren, Mustafa Tolga; Tirkaz, Caglar; Sonmez, Ozan; Yildiz, Eray (2017), “English/Turkish Wikipedia Named-Entity Recognition and Text Categorization Dataset”, Mendeley Data, v1 http://dx.doi.org/10.17632/cdcztymf4k.1
  
It is created by reducing the classes of the above dataset to 48 classes. It is shared over [Kaggle](https://www.kaggle.com/behcetsenturk/shrinked-twnertc-turkish-ner-data-by-kuzgunlar) due to Github file size restrictions.

## Question Answer
The dataset of [Kuzgunlar Turkish Electra Question-Answer Model](https://huggingface.co/kuzgunlar/electra-turkish-qa).
  
It is prepared using wikipedia contents to use with [TQUAD](https://github.com/TQuad/turkish-nlp-qa-dataset), which is an open source Turkish question-answer dataset.


## Sentence

It is a sentence dataset created by processing ~251 GB online Turkish pdf data for Masked LM applications. It is shared over [Kaggle](https://www.kaggle.com/rootofarch/kuzgunlar-acikhack-tr-sentence) due to the file size.

 - By using [TurkishDeasciifier](https://github.com/StarlangSoftware/TurkishDeasciifier), Turkish character misspelled words were rearranged in accordance with their original.

 - Using [Zemberek](https://github.com/ahmetaa/zemberek-nlp), the Turkish ratio of words in the sentence content was defined as 80% and above. In this way, overlooked non-Turkish pdfs and sentence quotations in foreign languages were tried to be avoided as much as possible.
