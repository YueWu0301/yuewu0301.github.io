---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here are several course projects~



## Airbnb Analysis
### 2024/5

**Abstract**:We first conducted an exploratory analysis of the data, then conducted relevant time series analysis, discovered quarterly changes in housing popularity, built multiple models for detailed regression analysis and testing, built a recommendation system based on the data, and, based on reviews, drew a word cloud diagram.


**Keywords**: EDA, time series analysis, regression, recommendation system

You can find our project website [here](https://yuewu0301.github.io/Airbnb_analysis/)


You can find our code&slides [here](https://github.com/YueWu0301/Airbnb_analysis)


-----

## Bilibili Analysis
### 2023/10
- Utilized techniques such as **ANOVA, two-way ANOVA, and ANCOVA** to **quantify the significant impact of factors** such as tags, gender, video length, and their interactions on the number of followers.

- Employed **GMM** fitting to **determine the boundary** between long, medium, and short videos on Bilibili with 6.17 and 18 minutes and explored the relationship between video length and the number of followers.

- Conducted variable selection using methods such as **RandomForest, Lasso,XGBoost and HDCSIS** to **identify the most relevant variables** to the number of followers for further analysis.

- Utilized methods such as **weighted least squares,  generalized linear models, and other 5 models** for **regression analysis** and provided **model interpretations**.

- Used **K-medoids** for content creator classification and designed **underestimation mechanism** to identify the most promising and cost-effective categories and video formats. Provided recommendations for content creator positioning.

You can find our project paper [here](../assets/bilibili_analysis.pdf)


You can find our code&slides [here](https://github.com/YueWu0301/Bilibili_analysis)


-----


## Exploratory Analysis on Customer Segmentation Data
### 2023/5
**Abstract**
In this post, we used data from kaggle related to credit card customers. We first carry out suﬀicient data
preprocessing, including data cleaning, data description and brief statistics description. After a series of variable adjustment and principal component analysis, we divided users into four categories, and each group showed
unique consumption habits and credit behavior. We also selected data related to credit limit according to distance
correlation, and classified customers by KMeans algorithm according to these data, and obtained customer groups
with low credit, medium credit and high credit. We also perform regression analysis on the credit limit, and
give a classification-based random forest regression method that performs better than the ordinary random forest
regression. Finally, we also discuss the mainstream clustering methods and the reasons for choosing KMeans in
this dataset.


**Keywords**: PCA , KMeans , Regression , Clustering ，Dimension Reduction，Feature selection

You can find our project paper [here](../assets/customer_analysis.pdf)


You can find our slides [here](../assets/customer_analysis.ppt)



---
## Exploratory Data Mining Based on New York City Taxi Data 
### 2022/10
- Based on **Pyspark**, 6 million taxi data were cleaned and preprocessed, and data visualization was performed using heat maps, Sankey diagrams, etc.
- Polynomial regression fitting is used to infer the taxi fare method in New York, and reasonable vehicle
dispatch suggestions are provided to taxi drivers in various regions to maximize profits.
- Combining the Spearman coefficient, random forest regression analysis, and XGboost regression analysis the relationship and importance of different factors (such as period, urban area, number of people) and
taxi travel prices were obtained.



<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
