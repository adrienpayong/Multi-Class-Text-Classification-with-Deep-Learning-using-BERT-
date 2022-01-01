### AG News Text Classification with BERT ###

This repository covers the code for performing text classification on the AG News dataset using state-of-the-art transformer model BERT.
AG News (AG’s News Corpus) is a sub dataset of AG's corpus of news articles 
constructed by assembling titles and description fields of articles, from the 4 largest classes (“World”, “Sports”, “Business”, “Sci/Tech”)
of AG’s Corpus.
BERT is a state-of-the-art transformer model use to perform complex NLP tasks like NLU, NLG, Sentiment Analysis,
Text Classification...., and it gives very high performance metrics with respect to these, sometimes even surpassing human capabilities.

Below are the steps to be followed:

1. Install the required packages stated in requirements.txt file 
   Packages can be installed on an Anaconda environment or on normal python interpreter.
   For Anaconda:
   conda create --name <youenvname>
   conda activate <yourenvname>
   pip install -r requirements.txt
   For Python Interpreter:
   pip install -r requirements.txt
   
2. The entire repository is modularised in to individual sections which performs specific task.
   First, go to src folder.
   Under src, there are 2 primary packages:
   a> ML_Pipeline:
   This contains individual modules with different function declarations to perform specific Machine Learning task.
   b> engine.py:
   This is the heart of the project, as all the function calls are done here.
   
3. Run/Debug the engine.py file and all the steps will be automatically taken care as per the logic.

4. All input datasets are stored in the input folder.

5. All predictions and models are stored in the output folder.

Texts are the most prevalent kind of data in the world today.
Text is a rich source of information, but since it is unstructured, extracting insights from it may be difficult and time-consuming.
As a result, having a robust text-processing system is vital and more than simply a must.
Today, there are several algorithms developed to conduct text classification, with BERT being one of the most prevalent.

Bidirectional Encoder Representations from Transformers (BERT) is a popular NLP model from Google that is famous for generating cutting-edge outcomes in a broad range of NLP jobs.Natural Language Processing (NLP) is very important in the field of artificial intelligence. The BERT method is based on ground-breaking concepts like seq2seq models and transformers. The seq2seq model is a network that can transform a given sequence of words into a new sequence and connect the words that seem to be more essential. This project will go through the application of the BERT basic model to text classification in great detail.
We'll see how this cutting-edge Transformer model can produce incredibly high-performance metrics for a big corpus of data with over 100k tagged training samples. 

## Data Explanation


We will be utilizing datasets from the hugging face collection for our case study.
The AG News dataset will be used to train the BERT model. 
- AG News (AG's News Corpus) is a subset of AG's corpus of news items that was created by combining the titles and descriptions of articles from the four largest classes.
- The four classes are as follows:
World, sports, business, and science/technology
- Each class in the AG News has 30,000 training and 1,900 test samples. 

## Aim
The project's goal is to create, train, and fine-tune the BERT model for classification on the AG News dataset. 

## Tech stack

 - Language - Python
 - Libraries – ktrain, transformers, datasets, numpy, pandas, tensorflow, timeit

## Environment

 - Jupyter Notebook

## Approach 

- Checking the hardware acceleration settings.
- Installing the required libraries
- Checking for the available dataset from the hugging face library
- Importing the required dataset
- Loading the train and test data
- Creating dataframe objects for train and test data.
- Performing data pre-processing
- Creating the BERT model.
- Compile the BERT model.
- Training the BERT model on some defined hyperparameters.
- Evaluating the performance metrics
- Saving the model.

 
