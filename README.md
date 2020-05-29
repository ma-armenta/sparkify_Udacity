# Sparkify Udacity Capstone Project

## Overview
Learn how to manipulate large and realistic datasets with Spark to engineer relevant features for predicting churn of a music service like spotify. How to use Spark MLlib to build machine learning models with large datasets, far beyond what could be done with non-distributed technologies like scikit-learn.

## Career Relevance
Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.

## Essential Skills
- Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes
- Use the machine learning APIs within Spark ML to build and tune models
- Integrate the skills you've learned in the Spark course and the Data Scientist Nanodegree program

## Libraries used
- pyspark
    * VectorAssembler, Normalizer, StandardScaler and PCA from ml.feature
    * LogisticRegression from ml.classification
    * MulticlassClassificationEvaluator from ml.evaluation
    * CrossValidator, ParamGridBuilder ml.tuning
    * Along with several as well as several functions from pyspark.sql.functions
- pandas
- matplotlib

## Interest
This project was very interesting and very helpful for those of us looking into moving to a Big Data environment of data science. Spark has similar APIs to those found in pandas and sklern, and has compatibility to program with small sets and turn them into pandas for verificationa and visualization, then implement with small changes on the code to run algorithms to scale.
As part of my interest and following the projects from Databricks, I also came accross the koalas project which uses the pandas APIs but uses the spark engine on the background. Really look forward to what that project will enable data scientist to do with much less transalation between spark and pandas APIs.