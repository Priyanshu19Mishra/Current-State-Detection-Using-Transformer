Current-State-Detection-Using-Transformer
(A comparitive analysis between GRU and Transformer) 

This repository is in continuation of the previous work on the "Current State Detection". The Previous work was based on the architecture of 
GRU, that worked on the sequential data in the text form. 
Optimizing the processing further, in this repository, we are working with the another powerful architecture for the textual data in the 
sequential formatting. Now we will be working with the "Transformers". The architecture of the Transformer has been added in the repository. 

Transformers are well known for thier workings with the long sequential textual data due to their remembering capacities. Looking to this 
promising approach of the transformers, it has been in used in place of GRU. 

This approach using transformer, works on the same classes/ labels as GRU worked on. 
The nine labels are
1. Stress
2. No stress
3. Depression
4. No depression
5. Bi-polar Disorder
6. Personality disorder
7. Mental
8. Non-Mental
9. Anxiety check

The result and the performaance of the model has been shared in the repository with multiple files. Images of the distribution of the  model
along with the performance of the model has been shared in the repository. 
The main source code file has been added in the repo with the title of "Psychology mood detection using transformer" the file contains the implementation.
The main task involves the integration of the dataset from the diversed categories. The data from the various categories were integrated into a single large 
dataset.
The huge data with around 2.5 lakh data has been shared in this repository. The pyhton file to built this huge dataset is also shared in this repository. 
This repository basically is the comparison of the working of the two architectures. The architecture that we are comparing here is GRU and transformers. Their 
working on the sequence to sequence textual data. Textual data are very very much important to process at the real world.
Development and deployment of the model for the mood detection can be implemented in various ways. One possible way is by using frameworks like Flask, Django to 
have connectivity at the back-end. Other could be using nqrok application. This application is supported in Google colab as well. And the most trendy and easy to 
deploy model could be using cloud services like AWS, Azure, etc. They even provide a handful of pre-trained models too for the user to directly query with the model.

There are various architectures of Transformers. SOme like, BERT, GPT, Peagasus, etc. In the following execution, bert transformer has been used. The most prefered
IDE for machine learning is Google colab.

