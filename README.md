# Analyzing-the-Online-Shopper-s-Purchasing-Intention-using-Clustering-Algorithm

![image](https://increasink.co.id/blog/ejechoof/2022/12/purchase-intention-adalah-1024x614.png)

[![Open In Jupyter Notebook](https://img.shields.io/badge/Open%20in-Jupyter%20Notebook-blue)](https://mybinder.org/v2/gh/username/repo/master?filepath=notebook.ipynb)     [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Anaconda-Server Badge](https://anaconda.org/anaconda/python/badges/version.svg)](https://anaconda.org/anaconda/python)

# Key Findings: The conversion rates of new visitors are high compared to those of returning customers

## Table of Contents

- [Project Title](#project-title)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Background](#background)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Methods](#methods)
- [Tasks](#tasks)
- [Contributing](#contributing)
- [License](#license)

# Project Title: Analyzing the Online Shopper's Purchasing Intention

# Installation of Anaconda

    Download the Anaconda distribution package from the official Anaconda website (https://www.anaconda.com/products/individual).
    
    Follow the installation instructions provided for your operating system (Windows, macOS, or Linux).
    
    Once the installation is complete, you can launch Anaconda Navigator, which provides a user-friendly interface for managing environments and launching Jupyter Notebook.

# Creating a Jupyter Notebook for Analyzing Shopper's Purchasing Intentions

    Open Anaconda Navigator and click on the "Launch" button under the Jupyter Notebook section.
    
    This will open a new browser tab with the Jupyter Notebook interface.
    
    Navigate to the directory where you want to create your notebook file.
    
    Click on the "New" button and select "Python 3" to create a new Jupyter Notebook file with a Python kernel.

# Reading Data into Jupyter Notebook

    Store the dataset file (e.g., "shoppers_data.csv") in the same directory as your Jupyter Notebook file.
    
    In a code cell, use the appropriate library (e.g., pandas) to import the necessary functions for reading data.
    
    Use the appropriate function (e.g., pandas' read_csv) to read the data file into a DataFrame.
    
    Assign the DataFrame to a variable for further analysis and exploration.
    
# Background
With the rise of online shopping, the number of consumers making purchases on the internet has steadily increased. However, despite the growing popularity of e-commerce websites like Amazon, many people tend to browse through products, add items to their wish lists or shopping carts, but ultimately refrain from making a purchase. This prevalent behavior highlights the necessity for tools and solutions that can tailor promotions and advertisements to online shoppers, thereby improving conversion rates. In this documentation, we will delve into an analysis of the various factors that impact a consumer's decision to make an online purchase.

 # Aims & Objectives
  Implement clustering and make recommendations based on the predictions. These recommendations will help you gain actionable insights and make effective decisions.
 
 # About the Dataset
 The following shows and describes the various numerical features of the dataset we are going to use:
 
 Adminstrative - pages such as profile page
 
 Administrative Duration - time spent on the administrative page in seconds
 
 Informational - Pages such as contact information
 
 Informational Duration - the amount of time in seconds spent on this page
 
 Product Related - Pages related to products on a website
 
 Product Related Duration - The amount of time spent of product related page
 
 Bounce rate - percentage of visitors who access the site from a page and then leaves the page without creating any request
 
 Exit Rate - represents the number of exits made from a particular page to leave the site
 
 Page Value - Refers to average value for a web page that a user visited before completing an e-commerce transaction
 
 Special Day - refers to days like mother's day
 
 The following are categorical features
 
 Operating Systems - I.e Windows,MacOs
 
 Browser - such as chrome,explorer,safari
 
 Region - Geograhical region
 
 Traffic Type - Source of the traffic either direct or through a different website
 
 Visitor Type - such as new,returning visitor or other visitor
 
 Weekend - whether or not the day is weekend
 
 Month - Month of visit
 
 Revenue - whether the sessions accumulated in a purchase
 
# Methods
Univariate Analysis

Bivariate Analysis

Clustering
 
# Associated Tasks

### Univariate analysis on the  following features:

• Revenue column 

• Visitor type

• Traffic type

• Region 

• Weekend-wise distribution

• Browser and operating system

• Administrative page

• Information page

• Special day
 
### Performing bivariate analysis between the revenue column and the 
following categories:

• Visitor type

• Traffic type

• Region

• Browser type

• Operating system

• Month

• Special day 
 
 
### Clustering

 - Performing K-means Clustering for Informational Duration versus Bounce Rate
 
 - Performing K-means Clustering for Informational Duration versus Exit Rate
 
 - Performing K-means Clustering for Administrative Duration versus Bounce Rate
 
 - Performing K-means Clustering for Administrative Duration versus Exit Rate
 
 
# Overview of Linear Relationship Outcomes

## Bounce Rate versus Exit Rate
![Bounce Rate versus Exit Rate](https://github.com/vonderwoman/Analyzing-the-Online-Shopper-s-Purchasing-Intention-using-Clustering Algorithm/blob/main/Output/Bounce%20Rate%20versus%20Exit%20Rate.png)
 
 
 
 
 
 
 
