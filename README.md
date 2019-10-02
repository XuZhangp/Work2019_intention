# HEM
This repo contains the implementation of "A deep neural architecture for sentence semantic matching" in Keras & Tensorflow.
# Usage for python code
## 0. Requirement
python 3.6  
numpy==1.16.4  
pandas==0.22.0  
tensorboard==1.12.0  
tensorflow-gpu==1.12.0  
keras==2.2.4  
## 1. Data preparation
The dataset is BQ.  
@inproceedings{chen-etal-2018-bq,  
    title = "The BQ Corpus: A Large-scale Domain-specific Chinese Corpus For Sentence Semantic Equivalence Identification",  
    author = "Chen, Jing  and
      Chen, Qingcai  and
      Liu, Xin  and
      Yang, Haijun  and
      Lu, Daohe  and
      Tang, Buzhou",  
    booktitle = "Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing",  
    year = "2018",  
    publisher = "Association for Computational Linguistics",  
    doi = "10.18653/v1/D18-1536",  
    pages = "4946--4951",  
}  
## 2. Start the training process
python siamese_NN_improved_loss_match.py  
