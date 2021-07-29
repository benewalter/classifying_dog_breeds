
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python version 3.0 or older.
The following libraries were used to complete the project: sklearn, tensorflow and keras, numpy, glob, random, cv2, matplotlib, tqdm, PIL.

Please note that the relevant bottleneck features of VGG16 could not be uploaded due to file size restrictions.


## Project Motivation<a name="motivation"></a>

As part of the Udacity Data Scientist Nanodegree, students are required to complete a Capstone project. I chose to complete the project on classifying dog breeds to fresh up my knowledge on CNNs. 

The notebook is structured as follows:

1. Testing dog and human face detectors

2. Creating a CNN from scratch to identify dog breeds

3. Using transfer learning to dramatically improve the CNN used for classifying dog breeds

4. Creating an algorithm that automatically detects humans or dogs in images and determines the (related) dog breed.



## File Descriptions <a name="files"></a>

The Jupyter notebook dog_app.ipynb provides all the code that was used for the analysis.
The images folder contains some images that were used as examples for the classification task.
The saved_models folder contains the relevant models that were trained and that can be loaded to classify images.
The bottleneck_features were used for the transfer learning. As described above, please note that the relevant bottleneck features of VGG16 could not be uploaded due to file size restrictions.

## Results<a name="results"></a>

The notebook exemplifies that with the help of libraries like KERAS, building a working CNN is really easy. However, while building such a CNN from scratch is relatively straight forward, the performance of such a CNN can often be rather mediocre. This can often result from missing training data, like it was the case for this project.
In these instances, transfer learning can be extremely valuable to improve the performance of the CNN dramatically. This was exemplified by this notebook.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I want to give credit to KERAS for providing excellent guidelines on how to easily create a CNN. Also, I relied on numerous posts on Stack Overflow when stuck with any question. 
I also want to thank the Udacity team for providing this code, the very useful instructions and guidelines for completing this project. 
Otherwise, feel free to use the code here as you would like! 

