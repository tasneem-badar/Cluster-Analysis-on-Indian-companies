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
The data for this project was collected from AmbitionBox, a platform providing detailed insights into companies, including ratings, reviews, salaries, and job openings. Using Beautiful Soup, a Python library for web scraping, relevant company attributes were extracted from the website.

The attributes gathered include company name, ratings, reviews, job openings, salaries, benefits, ownership status, company age, and more. This dataset formed the basis for clustering analysis, offering a comprehensive view of company characteristics to enable meaningful segmentation.

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

