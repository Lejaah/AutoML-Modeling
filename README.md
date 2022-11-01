# AutoML-Modeling
### Project Overview
In the previous project, you created the instructions needed to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images.
In this project, we are going to take the next step and build the classification model that would serve as the backbone of this product. (Don't worry, there's no coding involved!) For this task, we will use Google AutoML, an automated machine learning tool that will allow us to build the model and host it in the cloud. In order to appreciate how training data impact models, we will build models with 4 variants of the dataset. This project is designed to test your ability to

1. build a model using Google's AutoML Vision platform.
2. understand how properties of data impact performance of models.
### The Data
We'll be using the same [Kaggle chest x-ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) that we used in the previous project, except here, we'll skip the step of using Figure Eight's platform to label the data, and just use the original labels supplied with the data on Kaggle.
### The Four Parts of the Project
1. Create a binary classifier to detect pneumonia using chest x-rays
2. Create an unbalanced binary classifier
3. Create a binary classifier with dirty data
4. Create a three-class model with the classes “normal”, “bacterial pneumonia”, and “viral pneumonia”

#### Supporting Materials
* [AutoML Modeling Report](https://video.udacity-data.com/topher/2019/May/5ce43a30_automl-modeling-report/automl-modeling-report.pdf)
* [Automl-Modeling-Report(.docx)](https://video.udacity-data.com/topher/2019/October/5daac1f3_automl-modeling-report-all-fixed/automl-modeling-report-all-fixed.docx)
