# DonorsChoose Approval

![DonorsChoose Image](https://blog.tcea.org/wp-content/uploads/2017/06/Donors_choose_700-1.jpg)

This repository contains a machine learning project aimed at predicting whether teachers' project proposals submitted to DonorsChoose.org will be accepted or not. Check the [Jupyter Notebook](https://github.com/mudit-mishra8/donors-choose/blob/main/Donors%20choose%20project.ipynb) for detailed implementation.

## Table of Contents
- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Conclusion](#conclusion)

## Introduction
[DonorsChoose.org](https://www.donorschoose.org/) is an organization that empowers public school teachers to request materials and experiences for their students. With an increasing number of project proposals, it’s essential to efficiently screen these proposals to ensure they meet the criteria. The goal of this project is to predict whether a proposal will be accepted, based on text and metadata such as project description, teacher information, and school information. Predicting approval helps to streamline the review process and allows volunteers to focus on proposals requiring more attention.

## Data Cleaning
- Cleaned all the categorical, text and numerical features.
- Standardized text data in project descriptions to lowercase and removed any special characters and lot more.

## Feature Engineering
- Vectorized text data in project descriptions.
- Used tf-idf for text vectorization.

## Modeling and Evaluation
- Implemented various machine learning models for the classification task, such as Decision Trees, Random Forests, Logistic Regression, and more.
- Evaluated models using the AUC-ROC curve. The highest AUC achieved was 0.66. 

## Conclusion
This machine learning model aids DonorsChoose.org in pre-screening project proposals, enabling quicker and more efficient approval processes. This not only helps teachers get the funding they need more rapidly but also allows volunteers to concentrate on proposals that require more assistance.


