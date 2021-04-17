# MNIST-Custom-Dataset
## Files

- **Experiment log.ipynb** contains the problems which i had to solve to complete the project.
- **Experiment log.pdf** is the Screenshot of the **Experiment log.ipynb**.
- **Requirements.md** contains the list of libraries and their versions, which are required for this project.
## Task 2.1 
Use this dataset (https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip) to train a CNN. Use no other data source or pretrained networks, and explain your design choices
during preprocessing, model building and training. Also, cite the sources you used to borrow techniques. A test set will be provided later to judge the performance of your
classifier. Please save your model checkpoints. 

### Files
- **IIIT_MIDAS Task-1.ipynb is the iypnb** file, whivh consists the whole code for the task 2.1
- **Jupyter notebook Screenshot.pdf** is the complete screenshot of the iypnb file
- **The checkpoints** folder has the checkpoint of the model after every few epochs
 
## Task 2.2
Next, select only 0-9 training images from the above dataset, and use the pretrained network to train on MNIST dataset. Use the standard MNIST train and test splits
(http://yann.lecun.com/exdb/mnist/). How does this pretrained network perform is comparison to a randomly initialized network in terms of convergence time, final
accuracy and other possible training quality metrics? Do a thorough analysis. Please save your model checkpoints

### Files
- **Jupyter file-2.2-MNIST from scratch.ipynb** is the the iypnb file which consists the model with randomly initialised weights.
- **Jupyter file screenshot  IIIT_MIDAS-2.2-MNIST from scratch** is the screenshot of the iypnb file which consists the model with randomly initialised weights.
- **Jupyter file-2.2-training MNIST on predefined weights.ipynb** is the iypnb file which consists the model with weights from model trained by the 0-9 images of the dataset provided.
- **Jupyter file screenshot IIIT_MIDAS-2.2-training MNIST on predefined weights** is the screenshot of the iypnb file which consists the model with weights from model trained by the 0-9 images of the dataset provided.
- **Analysis and Comarison** File contains the thorough analysis between the 2 models.
- **checkpoints - only MNIST** Folder contains the checkpoints with the model of randomly initialised weights
- **checkpoints 2.2** Folder contains the checkpoints of the model with pre defined weiights

## Task 2.3
Finally, take the following dataset (https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip), train on this dataset and provide test accuracy on the MNIST test set, using the same test split from part 2. Train
using scratch random initialization and using the pretrained network part 1. Do the same analysis as 2 and report what happens this time. Try and do qualitative analysis of what's
different in this dataset. Please save your model checkpoints. 

### Files
- **jupyter file -2.3.ipynb** contains both the models of scratch random initialization and the pretrained weights.
- **jupyter file Screenshot 2.3.pdf** is the screenshot of the jupyter file.
- **Analysis and Comarisona.pdf** contains the thorough analysis between the 2 models.
- **checkpoints** contains the checkpoints of both the models. 


##

In all these Folders the Dataset folder has the images used as dataset
