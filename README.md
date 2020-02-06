# Cat Breed Classification Using CNN

### Overview

In this project, I built a machine learning model capable of classifying images of cat breeds on the Oxford-IIIT Pet Dataset [1]. The convolutional neural network (CNN) model built in this project has a better accuracy compare than a previous model created by Parkhi et al. [2]. Transfer learning is performed to transfer the knowledge of previously trained CNN in order to get a better accuracy.

**Attention:** the notebook was executed & tested using GPU. So please make sure the GPU is available to avoid unexpected error.

### Prerequisites (the installation cell is provided in the notebook):

- torch==1.3.1
- torchvision==0.4.2
- numpy==1.15.4
- pandas==0.24.2
- matplotlib==3.0.3
- tqdm==4.38.0
- sklearn==0.20.3`1
- seaborn==0.8.1

The dataset which will be used for this project can be downloaded by executing the 'Download' cell in the notebook.


### References
[1] https://www.robots.ox.ac.uk/~vgg/data/pets/

[2] https://www.robots.ox.ac.uk/~vgg/publications/2012/parkhi12a/