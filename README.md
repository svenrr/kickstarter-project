# Kickstarter Project 
The second project from our Data Science Bootcamp deals with crowdfunding by analyzing the data set of Kickstarter.

The data set contains about 200,000 projects from 22 different countries and from the period from 2009 to 2019.

Kaggle Dataset(s): https://www.kaggle.com/kemical/kickstarter-projects

---

**Goal:** How to raise money with crowdfunding?
* Recommendations and Insights for crowdfunding projects 
* Predicting the success of a project → Chances


**Business questions:**
* What does the average project on Kickstarter looks like?
* What can you expect with a specific project?
* Which factors are important for success? 
* Which machine learning model is the best to predict the success?   



**Recommendations:** 
* Don’t expect too much → just 25% of the projects got more than 7,000 USD
* Set a realistic goal - not too high (median goal of succesful projects was 3,500 USD) 
* Be aware of the different chances of success per category 
* Try to get featured (hints: https://www.kickstarter.com/blog/how-to-get-featured-on-kickstarter?lang=en)   


**Model results:** 

We tried the following models: KNN, Decision Tree, Logistic Regression, RandomForest

| Score  | KNN  | DT  | LR  | RF  |
|---|---|---|---|---|
| Recall  | 1  | 0.88  |  0.51 | 0.87  |
| AUC  | 0.58 | 0.67 | 0.65  | 0.7  |

→ RandomForest is our best model  

* We try to minimize False-Negatives (high recall)
* High recall is easily achieved, so we also need a metric to balance it out
* For this we are using the area under curve for precision-recall   



### In this repository you can find the following files: 
* Jupyter Notebook(s) 
* Presentation 
* Dataset(s)  


### Requierments
* Matplotlib
* Sklearn 
* Scipy
* Pandas
* Numpy
* Seaborn  


### Steps 
1. Imports 
2. Data Overview
3. Data Cleaning 
4. Exploratory Data Analysis
5. Data Preparation 
6. Machine Learning Models  
