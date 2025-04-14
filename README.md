

# Natural Language Processing Challenge

## Introduction

LLearning how to process text is an essential skill for any aspiring Data Scientist. In this project, I applied Natural Language Processing (NLP) techniques to build a model capable of identifying whether a news headline is real or fake.

## Project Overview

I worked with a dataset located in dataset/training_data.csv, which includes news headlines labeled as:

0 for fake news
1 for real news
My objective was to build a text classification model that can accurately distinguish between fake and real headlines.

Once my model was trained and validated, I used it to predict the labels in dataset/testing_data.csv. I then generated a new version of that file, replacing the placeholder label 2 with either 0 or 1, based on my model's predictions. I made sure to maintain the original file structure — no extra columns or formatting changes.


## Approach & Decisions

Like in a real-world scenario, I had the freedom to make my own choices regarding text preprocessing and modeling. I used several NLP techniques and common Python libraries to clean the text, extract features, and train a reliable classifier.
