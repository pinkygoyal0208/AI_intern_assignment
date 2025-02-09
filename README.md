NLP Projects: This repository contains two NLP (Natural Language Processing) projects implemented in Jupyter notebooks. The first project extracts tasks from text, and the second one analyzes sentiment from movie reviews.

Part A: Task Extraction from Text

A program that reads text and automatically finds tasks/action items in it. For example, if there's a sentence like "Rahul needs to submit the report by Friday", it will identify this as a task and extract who (Rahul), what (submit the report), and when (by Friday).

Features
1) Simple GUI interface to input text
2) Identifies tasks from paragraphs or long text
3) Extracts three main components:
	1) The actual task
	2) Who needs to do it (if mentioned)
	3) Deadline or timing (if mentioned)
4) Uses basic NLP techniques (no complex AI models)

How to Use
1) Open Task_Extraction.ipynb in Jupyter Notebook
2) Run all cells
3) A GUI window will pop up
4) Paste your text in the input box
5) Click submit to see extracted tasks

Used Libraries
1) NLTK for text processing
2) Tkinter for GUI
3) Regular expressions for pattern matching


Part B: Movie Review Sentiment Analysis

A program that can tell if a movie review is positive or negative. Uses the IMDB dataset loaded through pandas.

Features
1) Processes IMDB movie reviews
2) Classifies reviews as positive or negative
3) Shows accuracy and other performance metrics
4) Includes data preprocessing steps

How to Use
1) Open Sentiment_Analysis.ipynb in Jupyter Notebook
2) Run the cells in order
   
You'll see:
1) Data preprocessing results
2) Model training progress
3) Final accuracy scores
   
Used Libraries
1) Pandas for data handling
2) Scikit-learn for machine learning
3) NLTK for text preprocessing

Requirements
1) jupyter
2) pandas
3) nltk
4) scikit-learn
5) tkinter
6) Installation
