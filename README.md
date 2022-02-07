# TFPNER
## TFPNER: Exploration on the Named Entity Recognition of Token Fused with Part-of-Speech
Named entity recognition (NER), which aims at identifying real-world entity mentions from texts, is a fundamental task in natural language processing with a wide range of applications. 
Previous approaches mainly focus on the original pure sentence but the Part of speech (POS) contains rich semantic information and contribute to the success of the Natural Language Processing task. 
To further improve the performance of the NER task, we proposed the five methods that employed POS tags fused with the original tokens based on the BERT model to achieve the NER task, including concatenating token and POS as one or two sentences, adding POS embedding as one of the embedding elements, model ensemble, and conduct the multi-attention between the token representations and POS representations. 
In this work, we addressed the CoNLL-2003 and Groningen Meaning Bank (GMB) datasets which can provide both NER tags and POS tags. From our experiments on two datasets, part of the proposed methods can show performance improvement in comparison with the baseline methods.
### This is the project I worked with Haoqing Tang, the extraordinary computer scientist in CV & NLP area, during the interesting and memorable Postgraduate study period.
## Model
Here is the model we built to get the higher performance
### Token + POS
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/Token%2BPOS.png)
### Token + [SEP] +POS
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/Token%2B%5BSEP%5D%2BPOS.png)
### POS Embedding Layer
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/POS%20Embedding%20Layer.png)
### Token POS Attention
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/Token%20POS%20Attention.png)
### Model Ensemble
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/Model%20Ensemble.png)
## Result
![This is an image](https://github.com/Phoenix-JI/TFPNER/blob/main/Experimental%20Results%E2%80%93CoNLL-2003.png)
