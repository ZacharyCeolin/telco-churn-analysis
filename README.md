#Telco Customer Churn Analysis
This repository contains an exploratory data analysis project on customer churn at Telco telecommunications company. The goal is to understand the factors driving customer churn and provide insights to improve customer retention.

The dataset used to perform the analysis was the [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/abdallahwagih/telco-customer-churn) on Kaggle.

The analysis is divided into three R notebooks:

telco_churn.ipynb
Introduction and basic exploration of churned customers, including an overview of overall churn rate.

telco_churn_analysis.ipynb
Deeper analysis focused on the top three reasons for customer churn: Competition, Poor Customer Support, and Product/Service Dissatisfaction.

telco_churn_insights.ipynb
Final insights and recommendations based on the analysis to help Telco reduce churn.

Technologies and Libraries Used
The analysis is performed in R using the following packages:

install.packages(c("readxl", "ggplot2", "forcats", "dplyr", "maps", "patchwork", "viridis", "knitr"))

library(readxl)
library(ggplot2)
library(forcats)
library(dplyr)
library(maps)
library(patchwork)
library(viridis)
library(knitr)
