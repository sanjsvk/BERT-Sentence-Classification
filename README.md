# BERT-Sentence-Classification
BERT(Bidirectional Encoder Representations from Transformers) is used to train a text classifier 
<br>
<br>
Specifically, we will take the pre-trained BERT model, add an untrained layer of neurons on the end, and train the new model for our classification task.
<br>
<br>
We use BertForSequenceClassification from the Hugging Face library as a modification for fine tuning the BERT classifier.
