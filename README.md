# Information-in-Language
This is a fun little experiment where we are trying to understand the information carried in language! We attempt to measure the information content of various aspects of language by modeling them with a neural net that is optimized for minimal complexity. For more information, see the tutorial in 'Perceptron Networks' where the process of modeling and finding the complexity of the addition of two integers is explained.

Our initial toy models come from mathematics. We chose these statements since they are precise and we can easily generate training and validation datasets for them. We are starting with some proof of concept models using perceptron neural networks but will migrate to recurrent architecture to better represent statements that may not have a pre-determined length.

To get more meaningful results, we will model color naming conventions in different languages/cultures and determine their complexities. Using our technique, we will attempt to recreate the information theoretic aspects of the paper "Efficient compression in color naming and its evolution" by Zaslavsky, Kemp, Regier and Tishby (2018). We will also try to compare the similarities of different color naming conventions by training a minimal complexity network to recognize color naming conventions in multiple languages simultaneously. The difference between the summed network complexity required to model each language individually and the network complexity required to model both simultaneously can act as a measure of how similar two languages are. 

In addition, we will later model other, more complex, aspects of language such as kinship trees using recurrent neural networks so the network can handle variable length inputs. 

By looking at the trained weights of the networks, this project could help us understand the most efficient underlying structures for neural representations of language. It could also elucidate how growing up around different languages might change the way a person assigns meaning to phrases.

This paper provides a theoretical basis for the complexity of neural networks - http://math.bu.edu/people/mkon/nn30.pdf

Here is a link to the paper on color naming systems - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6077716/
