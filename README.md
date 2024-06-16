# Spam Filter Dataset

### Welcome to the GitHub repository for the Support Vector Analysis on a Spam Dataset. This repository contains a Jupyter notebook that demonstrates a SVC model to predict Spam or Not.

## Table of Contents
- Dataset
- Notebook Overview
- Dependencies
- Results
# Introduction
This project aims to illustrate the basics of SVM using a spam dataset. SVC is a fundamental statistical method used for predictive analysis, and this notebook is designed to be an introductory guide for anyone interested in learning about this technique.

## Dataset
**The dataset used in this analysis contains various features of mail, such as:**

| SPAM E-MAIL DATABASE ATTRIBUTES (in .names format)
|
| 48 continuous real [0,100] attributes of type word_freq_WORD 
| = percentage of words in the e-mail that match WORD,
| i.e. 100 * (number of times the WORD appears in the e-mail) / 
| total number of words in e-mail.  A "word" in this case is any 
| string of alphanumeric characters bounded by non-alphanumeric 
| characters or end-of-string.
|
| 6 continuous real [0,100] attributes of type char_freq_CHAR
| = percentage of characters in the e-mail that match CHAR,
| i.e. 100 * (number of CHAR occurences) / total characters in e-mail
|
| 1 continuous real [1,...] attribute of type capital_run_length_average
| = average length of uninterrupted sequences of capital letters
|
| 1 continuous integer [1,...] attribute of type capital_run_length_longest
| = length of longest uninterrupted sequence of capital letters
|
| 1 continuous integer [1,...] attribute of type capital_run_length_total
| = sum of length of uninterrupted sequences of capital letters
| = total number of capital letters in the e-mail
|
| 1 nominal {0,1} class attribute of type spam
| = denotes whether the e-mail was considered spam (1) or not (0), 
| i.e. unsolicited commercial e-mail.  
|
| For more information, see file 'spambase.DOCUMENTATION' at the
| UCI Machine Learning Repository: http://www.ics.uci.edu/~mlearn/MLRepository.html


1, 0.    | spam, non-spam classes

word_freq_make:         continuous.
word_freq_address:      continuous.
word_freq_all:          continuous.
word_freq_3d:           continuous.
word_freq_our:          continuous.
word_freq_over:         continuous.
word_freq_remove:       continuous.
word_freq_internet:     continuous.
word_freq_order:        continuous.
word_freq_mail:         continuous.
word_freq_receive:      continuous.
word_freq_will:         continuous.
word_freq_people:       continuous.
word_freq_report:       continuous.
word_freq_addresses:    continuous.
word_freq_free:         continuous.
word_freq_business:     continuous.
word_freq_email:        continuous.
word_freq_you:          continuous.
word_freq_credit:       continuous.
word_freq_your:         continuous.
word_freq_font:         continuous.
word_freq_000:          continuous.
word_freq_money:        continuous.
word_freq_hp:           continuous.
word_freq_hpl:          continuous.
word_freq_george:       continuous.
word_freq_650:          continuous.
word_freq_lab:          continuous.
word_freq_labs:         continuous.
word_freq_telnet:       continuous.
word_freq_857:          continuous.
word_freq_data:         continuous.
word_freq_415:          continuous.
word_freq_85:           continuous.
word_freq_technology:   continuous.
word_freq_1999:         continuous.
word_freq_parts:        continuous.
word_freq_pm:           continuous.
word_freq_direct:       continuous.
word_freq_cs:           continuous.
word_freq_meeting:      continuous.
word_freq_original:     continuous.
word_freq_project:      continuous.
word_freq_re:           continuous.
word_freq_edu:          continuous.
word_freq_table:        continuous.
word_freq_conference:   continuous.
char_freq_;:            continuous.
char_freq_(:            continuous.
char_freq_[:            continuous.
char_freq_!:            continuous.
char_freq_$:            continuous.
char_freq_#:            continuous.
capital_run_length_average: continuous.
capital_run_length_longest: continuous.
capital_run_length_total:   continuous.


**The target variable is the spam of the dataet.**

## Notebook Overview
**The notebook is divided into the following sections:**

**Introduction:** Brief overview of the project.
**Data Loading and Preprocessing:** Loading the dataset and preparing it for analysis.
**Model Building:** Creating and training the linear regression model.
**Model Evaluation:** Assessing the performance of the model.
**Conclusion:** Summary of findings and potential improvements.

## Dependencies
**To run the notebook, you will need the following Python libraries:**

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Results
**The SVM model provides best score after analysing the dataset**
