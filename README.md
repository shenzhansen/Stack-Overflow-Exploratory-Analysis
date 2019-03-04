# Stack-Overflow-Exploratory-Analysis
The final project contributed by Zhansen Shen, Yuhan Liu and Yuting Wang for Big Data Analytics EECS 6893

1. Overview
This is an auto-tagging system which can first realize auto tagging, this is a user-friendly feature to make it easier for user to decide while reducing mistakenly classified tags. Another objective is to find out factors and analyze components leading to a high-score question based on linear regression

2. Dataset
The dataset is from Stack Overflow Q&A website are used containing 10% of total questions and answers. Our dataset contains 1264216 questions, 2014516 answers, 37034 tags. Total size or the sample is 3.5 gigabytes.

Three tables are in this dataset: Answers.csv, Questions.csv and Tags.csv. Answers include ID, owner user ID, creation date, parent ID and their score and body. the Parent ID are associated with the questions.csv. Questions are composed of ID, owner user ID, creation date and closed date, score, title and body. Tags relate tags to each question.


3. Software Package Installation
python 
pandas
Gephi

