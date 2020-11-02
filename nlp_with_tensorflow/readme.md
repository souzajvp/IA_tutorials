# Natural language processing with TensorFlow

This is a tutorial provided in [TensorFlow](https://www.youtube.com/watch?v=fNxaJsNG3-s&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S) youtube channel.

## Brief summary of NLP

<blockquote>
Natural Language Processing or NLP is a field of Artificial Intelligence that gives the machines the ability to read, understand and derive meaning from human languages.
</blockquote>

[Source](https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1)

The first thing we must have in mind the differences of **human** and **machine language**... <br>

While we are great at interpreting tone, facial and body expression, irony and a lot of nuances in speech and text... well, machines are not (or at least not in the same way as we do).<br>
So the first step would be to convert data from human language to machine language. While there are many ways to do it, one that is quite simple and used in the tutorial from [TensorFlow](https://www.youtube.com/watch?v=fNxaJsNG3-s&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S) is Tokenization. <br>
Briefly, Tokenization aims at chopping large contents of text into small chunks. Then we can assign numbers or "keys" for each Token, in every line of text that we are working on. This strategy creates something like a dictionary and we can use this dictionary to transform every sentence into a set of keys. <br>
Then we end up with a structure that grealy resemble matrices... and as everybody knows, the computer works quite well with numbers. In fact, in Python we can use numpy or other packages to speed up the process.<br>
After this fragmentation is done, we can then feed these matrices to our model and train it. In the case of this small project, we are working in a Supervised Manner, meaning that we tell the algoritghm which sentences are "Sarcastic" and which are "Non-Sarcastic". Then, our model does its magic, by learning the "weight" of tokens and how these tokens impact the label of each sentence...

#### But... do not take it from me. Here are some articles from people that actually know about it!

1. [Your Guid to Natural Language Processing](https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1);
2. [An Introduction to Natural Language Processing (NLP)](https://medium.com/@ODSC/an-introduction-to-natural-language-processing-nlp-8e476d9f5f59);
3. [Data Science por Brasileiros — Introdução a (NLP) - Article in Portuguese](https://medium.com/@adilmarcoelhodantas/data-science-pt-nlp-70c696b59f00);
4. [Natural Language Processing (NLP) Zero to Hero](https://www.youtube.com/watch?v=fNxaJsNG3-s&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S).
