# PatternRecognition
------

In view of the characteristics of different picture shooting angles, abundant text types, weak text context connection and lacking of samples in store scene classification task, we propose a multi-stage model based on neural network, which is characterized by text information. 
The algorithm is combined with two submodules—text detection and recognition, semantic classification. First, a text detection and recognition network based on DBNet and CRNN is designed while text orientation classifier and augmented dataset technology are introduced to improve the accuracy of image text extraction. Second, the derived text acts as input to the Ernie text recognition migration model network. Finally, the store scene image classification of the verification set is derived. 
Our model is tested on large public datasets, and the experiment shows that the proposed method can extract the features of store scene images well and classify them effectively according to the derived text. Compared with former algorithms, the proposed method improves both the classification robustness and generalization ability of the model.
