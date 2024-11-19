# Natural-Language-Processing-Named-Entity-Recognition
Named Entity Recognition using Word2Vec, POS Tagger and LSTM.

Named Entity Recognition (NER) is a NLP task in which we are interested in locate and classify named entities mentioned in a text, a named entity is a real world object that can be denoted with a proper name. There are several types of named entities, in our case we are interested in six of them: person, corporation, location, product, group and creative work. As most NLP tasks, to obtain high performance NER requires analysis of the text as a sequence of tokens, this allows the model to capture the context of each word and classify them according to their contexts.

Transformer-based architectures were not allowed in project specification.

Two different model architectures have been proposed to solve our NER task. The baseline architecture is composed by a word embedding layer, a multi-layers bidirectional LSTM and a dense layer used to make the final classification step. Then the baseline architecture has been improved by adding an external POS Tagger and more dense layers for the classification step.

More information and the results in `report.pdf`.

