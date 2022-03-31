# Portfolio
Hello,

I'm Phuc, or Patrick, borned and raised in a beautiful town in the middle of Vietnam, an engineer currently pursuing a Master Degree in Data Science, a data analyst enthusiast with a strong business sense. I thrive on digging into complex business problems, producing insightful, strategic recommendations, and implementing data-driven solutions.

As hobbies, I spend a lot of time playing football casually and competitively (Wing-back). I am also a gaming nerd (FIFA and CS:GO)

...

### Projects list

| Projects      | Tag | Type     |
| :---        |    :----:   |          ---: |
| BI Digital Transformation | `BI`, `DE`       | Professional   |
| [Cryptocurrency forecasting](Forecasting-Cryptocurrency-Prices-Time-Series) | `DL`       | Educational   |
| Customer Segmentation for Marketing | `ML`       | Educational   |
| E-commerce Operations Dashboard | `BI`, `DE`, `Visualization`       | Educational   |
| [FIFA Dashboard visualization](Visualization:-FOOTBALL-GENERATIONS-IN-COMPARISION) | `Visualization`       | Educational   |
| Forecasting Model for multi-stores company | `ML`, `MLOps`  | Educational  |
| [Income prediction modelling](Predictive-modeling) | `ML` | Educational   |
| [Market Basket Analysis](Market-Basket-Analysis:-THE-FAMOUS-INSTACART-PROBLEM) | `ML`, `MLOps` | Educational   |
| [Metrics for Machine Translation](Machine-translation) | `DL`, `NLP`      | Educational   |
| Online shop database design  | `DE` | Educational   |
| Supply Chain Operations excellence | `Management`, `SCM` | Professional   |
| Recommendation system for Online Shopping | `ML` | Educational   |
| Supply Chain KPIs & Dashboard design | `Management`, `BI`, `Visualization`| Professional   |      

 <font size="1"> (*) Abbreviation: BI: Business Intelligence | DE: Data Engineering | DL: Deep Learning | ML: Machine Learning | NLP: Natural Language Processing | SCM: Supply Chain Management </font> 
---
## Machine Learning
---

### Market Basket Analysis: THE FAMOUS INSTACART PROBLEM

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()
[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)]()
[![Open Report](https://img.shields.io/badge/PDF-Open_Report-blue?logo=AdobeAcrobatReader)]()
[![Open Presentation](https://img.shields.io/badge/PDF-Open_Presentation-blue?logo=AdobeAcrobatReader)]()

<div style="text-align: justify">The project objective is to explore the famous dataset Instacart. First we did Exploratory Data Analysis with different aspect such as buying patterns by product, hour of day, day of week and product category. The insights gathered from the analysis are then utilized to build the Apriori algorithm with 2 different approach: inter-department and intra-department to predict the basket of the customer</div><br>
<div style="text-align: justify">Finally, a dashboard combining the EDA and a recommendation system built from the result of the Apriori algorithm is deployed to help the business stakeholder develop their customer experience.</div>
<br>
<img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/MBA.JPG?raw=true"/>

---
### Predictive modeling

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()
[![Open Report](https://img.shields.io/badge/PDF-Open_Report-blue?logo=AdobeAcrobatReader)]()


<div style="text-align: justify">The project presents the results of applying machine learning methods suitable for predicting income from the proposed dataset using supervised machine learning algorithms: Logistic Regression, Linear Discriminant Analysis, K-Neighbors, Decision Tree, Gaussian Naive Bayes, Random Forest, Support Vector, Gradient Boosting, and Ada Boost algorithm, and compare their performances to obtain the best performing classifier and then use Stacking to increasing the predictive force of the classifier.</div><br>

<div style="text-align: justify">The result is that the best model is the stacking model. However considering the efficiently in training and predicting time. The final decision  is the Gradient Boosting model using GLMM encoding method</div><br>

<b>Keywords:</b> GLMM, Logistic Regression, Random Forest, Gradient Boosting, and Stacking classifier.
<br>
<img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/Predictive_modelling.JPG?raw=true"/> 

---

### Visualization: FOOTBALL GENERATIONS IN COMPARISION

[![Open Web App](https://img.shields.io/badge/Heroku-Open_Web_App-blue?logo=Heroku)]()
[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)]()
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()

<div style="text-align: justify">The dashboard created aims to inspect some questions that all the football-lovers mind. How will be the next generation of football players? What will happen after the decade of Messi and Ronaldo?
</div><br>
<div style="text-align: justify">The dashboard was created with Plotly, an interactive graphing library for Python. With Plotly, we developed the main interactions that are necessary to tell the story we are interested to transmit. The second objective of this project was to create a more pleasant experience for the user, and to improve the layout we used HTML, CSS and a framework from CSS called Bootstrap. In this way we achieved a better organization of our Dash App and the users can navigate through the sections like a normal web page
</div>
<br>
<img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/FFDash.JPG?raw=true"/>

---
### Machine translation 
A regression approach on the Most Recent Metrics for Machine Translation

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()

<div style="text-align: justify">The purpose of this project is to create a metric that best correlates with human assessments of  machine translation quality. We tried different available scoring metrics such as ROUGE, BLUE, BLUERT (most advanced metrics) with different n-grams setting. Finally, an ensemble approach was used as the scores generated from the metrics are used as features for a regressor (Gradient Boosting ModelS) to finally predict the score</div><br>
<div style="text-align: justify">The result showed that the ensemble modelling did show a significant improvement from the original scoring metrics. However performance and time constraint is still the problem with this approach 
</div>
<br>
<img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/TM.JPG?raw=true"/>

---
### Forecasting Cryptocurrency Prices Time Series

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)]()
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()

<div style="text-align: justify">The project is to build and benchmark predictive models  for timeseries forecasting using deep neural networks: LSTM, GRU and Bi-LSTM. We tested the models with basic L1 regularization, grid-search for hyper-parameter tunning and using RMSE for models validation. Finally, we compared the result of uni-variate and multi-variate timeseries forecasting
</div>
<br>
<img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/DL.jpg"/> 
---
### Introduction to Recommendation system

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/ames-house-price.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/kaggle-house-price/blob/master/ames-house-price.ipynb)

<div style="text-align: justify">Project applied several approach such as RFM analysis and perfrom customer clustering with K-Mean. For the Cold-start problem: The top 10 best-selling products will be used to create a recommender system for new users. Fot the RecSystem, we applied collaborative filtering techniques by comparing different models Bayesian Personalized Ranking (BPR), Logistic Matrix Factorization (LMF), Alternative Least Square (ALS). The evaluation metrics used are <b>Precision at K</b> and <b>Hits rate</b>
</div>
<br>
<center><img src="https://github.com/phucnh22/phucnh22.github.io/blob/main/images/RS.JPG?raw=true"/></center>
---
<center>© 2021 Phuc Nguyen. Powered by Jekyll and the Minimal Theme.</center>
