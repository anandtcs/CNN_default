#Base 

###[ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)



#CNN for NLP:


###[Effective Use of Word Order for Text Categorization with Convolutional Neural Networks](https://arxiv.org/pdf/1412.1058v2.pdf)
This paper studies CNN on text categorization to exploit the 1D structure (namely, word order) of text data for accurate prediction. Instead of using low-dimensional word vectors as input as is often done, we directly apply CNN to high-dimensional text data, which leads to directly learning embedding of small text regions for use in classifi- cation. In addition to a straightforward adaptation of CNN from image to text, a simple but new variation which employs bag-ofword conversion in the convolution layer is proposed.


Interesting because show a clear application of CNN to text data


###[Unsupervised Learning of Sentence Representations using Convolutional Neural Networks](https://arxiv.org/pdf/1611.07897v1.pdf)
The word-to-vector representation is used, and convolutional neural networks are employed as sentence encoders, mapping an input sentence into a fixed-length vector. This representation is decoded using long short-term memory recurrent neural networks, considering several tasks, such as reconstructing the input sentence, or predicting the future sentence


Uses the encoder - decoder model


###[Modeling Interestingness with Deep Neural Networks](https://www.microsoft.com/en-us/research/wp-content/uploads/2014/10/604_Paper.pdf)
describe how to learn semantically meaningful representations of sentences that can be used for Information Retrieval. The example given in the papers includes recommending potentially interesting documents to users based on what they are currently reading. The sentence representations are trained based on search engine log data.
	Similaire :
A Latent Semantic Model with Convolutional-Pooling Structure for Information Retrieval.


###[Learning Semantic Representations Using Convolutional Neural Networks for Web Search](https://pdfs.semanticscholar.org/8478/c0f46dd30ef7f4052145983d6d315c2e1f17.pdf)


###[Convolutional Neural Networks for Sentence Classification](http://www.aclweb.org/anthology/D14-1181)
Convolutional neural networks (CNN) trained on top of pre-trained word vectors for sentence-level classification tasks.


Our baseline model with all randomly initialized words (CNN-rand) does not perform well on its own. While we had expected performance gains through the use of pre-trained vectors, we were surprised at the magnitude of the gains. Even a simple model with static vectors (CNN-static) performs remarkably well, giving competitive results against the more sophisticated deep learning models that utilize complex pooling schemes
	
Similaire : [A convolutional neural network for modelling sentences](https://arxiv.org/pdf/1404.2188.pdf?utm_medium=App.net&utm_source=PourOver)


###[Relation Extraction: Perspective from Convolutional Neural Networks](http://www.cs.nyu.edu/~thien/pubs/vector15.pdf)
CNNs for Relation Extraction and Relation Classification tasks. In addition to the word vectors, the authors use the relative positions of words to the entities of interest as an input to the convolutional layer. This models assumes that the positions of the entities are given, and that each example input contains one relation. 


Similaires : 
Sun, Y., Lin, L., Tang, D., Yang, N., Ji, Z., & Wang, X. (2015). Modeling Mention , Context and Entity with Neural Networks for Entity Disambiguation, (Ijcai), 1333–1339. 


 Zeng, D., Liu, K., Lai, S., Zhou, G., & Zhao, J. (2014). Relation Classification via Convolutional Deep Neural Network. Coling, (2011), 2335–2344.


#Hors série mais intéressant :


###[Text detection with convolutional neural networks](https://pdfs.semanticscholar.org/fd79/0b061082571e20be7892ce4a97e156497c9f.pdf)
The CNN model learns on cropped text patches and non-text scene patches to discriminate between the two. The text are then detected on the response maps generated by the CNN filters given the multiscale image pyramid of the input. To reduce the search space for text detection

related : C. Zhang, C. Yao, B. Shi, and X. Bai, “Automatic discrimination of text and non-text natural images,” in ICDAR, 2015

###[Grounded Compositional Semantics for Finding and Describing Images with Sentences](https://tacl2013.cs.columbia.edu/ojs/index.php/tacl/article/download/325/45)
Easy to  produce compositional feature vectors for accurately representing and classifying sentences or images. However, the sentence vectors of previous models cannot accurately represent visually grounded meaning. 
They introduce a model which uses dependency trees to embed sentences into a vector space in order to retrieve images that are described by those sentences. 
It learns  to map sentences and images into a common embedding space in order to be able to retrieve one from the other



#RNN for Image :

###[Recurrent Convolutional Neural Networks for Scene Labeling](http://jmlr.org/proceedings/papers/v32/pinheiro14.pdf)
Use recurrent architecture  of the composition of P instances of the “plain” convolutional network 

###[Recurrent Convolutional Neural Network for Object Recognition](http://www.cv-foundation.org/openaccess/content_cvpr_2015/app/2B_004.pdf)

Character level : (to read)


Learning Character-level Representations for Part-of-Speech Tagging.
Character-level Convolutional Networks for Text Classification
Character-Aware Neural Language Models.
