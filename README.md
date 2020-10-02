# NLP-projects

Three small NLP projects to understand the process from data cleaning to training and generating text in Keras. 


##### Proj 1: Metamorphosis book generator:

Text generation where given inputs size 50, our text generator will generate the 51th word. 

##### Proj 2: Hotel description generator: 
Similar to previous project, but this time the inputs had varying n-grams padded to the samel length.

##### Proj 3:Machine translation :  
Tutorial for creating a seq2seq model in keras for translating from english to french


# Project status 
1)	Metamorphosis generator completed

2)	Hotel description generator completed
 
3)	Machine translation at word level not completed, some bugs unresolved

# Reflection
Project goals: To get more mastery and practice in NLP projects with LSTM

Learnt that there are different model types in Keras, and how they require different architect, how to pre-process the text inputs using the NLTK library and using the Tokenizer class from keras to prepare different text inputs. 

One difficulty was trying to understand the process of generating text in Hotel description and metamorphosis generator. I took some time to read and understand how the code was able to take the output from previous timestep and append it into our previous input sequence while maintaining the length of the input sequence through padding. 

#### Under machine translation: 

Learnt how to use the glove embedding matrix as our embedding layer.

Learnt how to use the functional API in keras.


#### Tutorials inspired from: 


Brownlee, J. (2017). Long short-term memory networks with python. Machine Learning Mastery. Retrieved from https://machinelearningmastery.com/deep-learning-with-python.

https://keras.io/examples/nlp/lstm_seq2seq/

https://stackabuse.com/python-for-nlp-neural-machine-translation-with-seq2seq-in-keras/

https://www.tensorflow.org/tutorials/text/text_generation

https://towardsdatascience.com/automatically-generate-hotel-descriptions-with-lstm-afa37002d4fc



