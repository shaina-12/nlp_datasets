# Italian NLP Corpus - Classification/Sentiment Analysis
## Description

__Corpus of Sentences rated with Human Complexity Judgments__

This corpus contains 1,123 Italian sentences and 1,200 English sentences rated by humans with a judgment of complexity. Judgments were collected through a crowdsourcing task in which 20 native speakers of each language were asked to judge how difficult they perceived a given sentence on a complexity scale from 1 (i.e. “very easy”) to 7 (i.e. “very difficult”). 

The datasets of sentences used for the task were taken from two different manually revised treebanks: the newspaper section of the Italian Universal Dependency Treebank (IUDT) for the Italian experiment, and the automatically converted Wall Street Journal section of the Penn Treebank for the English experiment."


___Brunato D., De Mattei L., Dell’Orletta F., Iavarone B., Venturi G. (2018) “Is this Sentence Difficult? Do you Agree?“. In Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing (EMNLP 2018), 31–4 November, Bruxelles.__


## Entries

 train: 
 * Italian 1,123 sentences
 * English 1,200 sentences


## URL
http://www.italianlp.it/

## Format
text - csv  

| Column | Description        |
| ----- | ------------------ |
|class_index | a number from 1 to 5 |
|review | the text of the review |

## Example
<pre>
951583636,parla dei profughi in arrivo dal Ruanda.,1,4,2,4,1,1,1,1,2,1,2,1,1,2,1,2,3,1,1,1</pre>

