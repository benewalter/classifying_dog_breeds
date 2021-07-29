
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python version 3.0 or older.
The following libraries were used to complete the project: sklearn, tensorflow and keras, numpy, glob, random, cv2, matplotlib, tqdm, PIL.


## Project Motivation<a name="motivation"></a>

As part of the Udacity Data Scientist Nanodegree, students are required to complete a Capstone project. I chose to complete the 

I explored the following questions:

1. Are developers with a higher salary more satisfied?

2. To which extent do the working hours influence job satisfaction?

3. Do experienced programmers tend to be more satisfied than their less experienced colleagues?

In addition to these questions, which are also addressed in the related Medium post under (...), I explored whether using these three variables, one could build a machine learning model that enables predicting job satisfaction of developers. To this end, I tested a logistic regression, a decision tree, and a random forest model.


## File Descriptions <a name="files"></a>

The Jupyter notebook analyzing_job_satisfaction.ipynb provides all the code that was used for the analysis.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://benewalter.medium.com/how-to-become-a-satisfied-developer-lessons-from-the-2020-stack-overflow-developer-survey-7faf3b6c63ab).
The results indicate that satisfied developers represent a heterogenous group consisting of individuals working both short and long hours and either being decades long experts in their field or having started only some years ago. Only a higher salary seems to be related with job satisfaction. Furthermore, the exploration revealed that the three examined variables do not enable to build a good machine learning model to predict job satisfaction.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I want to give credit to Stack Overflow for the data. Also, I relied on numerous posts on Stack Overflow when stuck with any question. 
I also want to thank Josh and the rest of the Udacity team for providing this code, the very useful instructions and guidelines for completing this project. 
Otherwise, feel free to use the code here as you would like! 

