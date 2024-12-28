# Cluster Analysis on Indian Companies

Segmented Indian companies based on key attributes using PCA and clustering techniques like K-Means and Agglomerative Clustering. The analysis identified distinct groups, providing insights into company characteristics and market segmentation.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Collection](#data-collection)
3. [Features](#features)
4. [Methodology](#methodology)
5. [Requirements](#requirements)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results](#results)
9. [Contributions](#contributions)
10. [License](#license)
---------------------
## Project Overview
This project segments Indian companies based on ratings, reviews, jobs, salaries, and company age. By applying PCA, the data was reduced to two principal components for easier visualization, and clustering techniques like K-Means and Agglomerative Clustering identified two groups of companies:

1. Growing firms with higher reviews, jobs, and salaries.
2. Established firms with higher ratings and older ages.

The results provide insights into market segmentation, aiding strategic decision-making.

---------------------------
## Data Collection
The data for this project was collected from [**AmbitionBox**](https://www.ambitionbox.com/), a platform offering detailed insights into companies, including ratings, reviews, salaries, and job openings. Using **Beautiful Soup**, a Python library for web scraping, key company attributes were extracted to form the dataset.

------------------------
## Features 

1. Name: Name of the company.
2. rating: Rating of the company.
3. company_type: The type of service provided by the company.
4. Employee_count: Number of employees in the company.
5. ownership_status: Ownership_status of the company, which would be private or public.
6. company_age: Age of the company.
7. head_quarters: Location of company headquarter.
8. reviews: The number of reviews about the company.
9. Salaries: The number of entries talking about the salary the company offers.
10. Interviews: The number of interviews conducted by the company.
11. Jobs: The number of job openings or positions in the company.
12. Benefits: Number of entries discussing the company's benefits.

--------------------

## Methodology

The project follows these main steps:

1. **Web Scraping**:
   - Data was collected by scraping car listing information from [AmbitionBox](https://www.ambitionbox.com/) using BeautifulSoup.

2. **Data Preprocessing**:
   - Cleaning the data and handling missing values.
   - Preparing the dataset for analysis by scaling numerical features and selecting relevant features.

3. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of car prices to understand price patterns.
   - Identified key features that significantly impact car prices.
   - Visualized trends across different car models, brands, and locations.

4. **Data Encoding**:
   - Transformed data as needed, including encoding and scaling, to improve model performance.

6. **Outlier Detection**:
   - Identified outliers using the Interquartile Range (IQR) and box plot methods.

7. **Outlier Treatment**:
   - Applied trimming, quantile-based flooring & capping and log transformation to handle outliers and normalize the data distribution.
  
8. **Cluster Analysis**:
   - Applied Cluster Analysis using:
     - **K Means Clustering**
     - **Agglomerative Clustering**
    
## Requirements

- Python 3.x
Install all dependencies using:

```bash
pip install -r requirements.txt
```
## Installation 

To set up the project on your local machine, follow these steps:

**Clone the Repository**:

```bash
git clone https://github.com/tasneem-badar/Market-Trend-Analysis-and-Price-Prediction-on-Used-Cars.git
cd cluster Analysis on India Comapnies
```

