
# Market-Segmentation-Analysis

This project explains the step by step implementation of Market Segmentation

## Table of contents

- [Market Segmentation Analysis]()
- [Market Segmentation in Medical Market]()
- [Market Segmentation in Tourism Industry]()

## Requirements

Python 3.6 or later with the following `pip3 install -r requirements.txt` packages:

- ipython==8.4.0
- matplotlib==3.5.2
- numpy==1.15.1
- pandas==1.4.2
- pca==1.8.2
- plotly==5.8.2
- scikit_learn==1.1.1
- scipy==1.8.1
- seaborn==0.11.2
- statsmodels==0.13.2
- yellowbrick==1.4

## Market Segmentation Analysis

Conceptually, market segmentation sits between the two extreme views that

(a) all objects are unique and inviolable and

(b) the population is homogeneous

Market segmentation means cutting markets into slices.
The segmentation criterion can be one single consumer characteristic, such as age, gender, country of origin, or stage in the family life cycle.
It contains a larger set of consumer characteristics, such as a number of benefits sought when purchasing a product, a number of activities undertaken when on vacation, values held with respect to the environment, or an expenditure pattern.

### The Benefits of Market Segmentation
- At the most general level, market segmentation forces organizations to take stock of where they stand, and where they want to be in future.
- In doing so, it forces organizations to reflect on what they are particularly good at compared to competitors, and make an effort to gain insights into what consumers want.
- Market segmentation offers an opportunity to think and rethink, and leads to critical new insights and perspectives.
- When implemented well, market segmentation also leads to tangible benefits, including a better understanding of differences between consumers, which improves the match of organizational strengths and consumer needs.

## Market Segmentation in Medical Market

### Target: 
Task is to analyze the Medical Market in India using Segmentation analysis and come up
with a feasible strategy to enter the market, targeting the segments most likely to use their
product in terms of Geographic, Demographic, Psychographic, Behavioral.

### Techniques and Algorithms:
Machine learning using python with pandas, scikit-learn and k means clustering.

In this project we are using [Census 2011](https://censusindia.gov.in/census.website/data/census-tables) data for the analysis. The Census 2011 is the 15th National census survey conducted by the Census Organisation of India. Mr. C. Chandramouli is the Commissioner & Registrar General of the Indian 2011 Census. 
We are using the K-means clustering algorithm to find groups which have not been explicitly labeled in the data. This is used to confirm assumptions about what types of groups exist or to identify unknown groups in our data sets.
We conduct surveys on various government policies and budgets concerning healthcare services In India. We also use Fermi Estimation to estimate the size of the market for health checkup services in India.

### Result:
Segmentation analysis is an important step before we begin on a marketing plan. Hence, it is important to learn how to analyze our audience and market. By analyzing the trends, we observe that India's healthcare service market is showing immense potential and attracting huge investors. We found that the majority of the market related to households with an Internet and a high literacy rate and those in the age group of 30-49. However, we discovered that focusing on specific groups of clients or markets provides the highest profit for the company and aids in the establishment of a stronger base.

## Market Segmentation in Tourism Industry

### Techniques and Algorithms:
Machine learning using python with pandas, scikit-learn and k means clustering.

In this project, we are using [Google Travel Review Ratings Data Set](https://archive.ics.uci.edu/ml/datasets/Tarvel+Review+Ratings). This data set is populated by capturing user ratings from Google reviews. Reviews on attractions from 24 categories are considered. User rating ranges from 1 to 5 and average user rating per category is calculated. We perform segmentation analysis in which we target the segments most likely to use our product in terms of Geographic, Demographic, Psychographic, Behavioral.
We perform the EDA to get some initial investigations on the dataset to discover the structure and the content of the dataset. The distribution of ratings in each attraction category differs. Some have a wide range of distribution, while others are concentrated in low-rated areas. 
We created the ‘Freemium Business Model’ for our travel recommendation system.

### SERVICE DESCRIPTION:
#### Customers:
Free users can directly access the recommendation systems and find the popular places in specific locations or destinations and their travel. They can also book hotels and flights from the platform. Premium users pay the subscription fee for special offers and discounts on hotels and flights. They also get extra information of different nearby locations from their destination.

#### Flight and Hotel Booking:
Different travel agencies and lodging services are available to our customers. Travelers can use the site to order tickets as well as take advantage of various discounts. Travelers look for a place to stay in a specific location and compare possibilities based on price, amenities, and other factors. The traveler pays the amount specified by the hotel owners plus a transaction fee when making a reservation through our site. The traveler stays at the hotel, and after deducting their commission, we pay the money to the hotel owners. The general public is given access to reviews from hotel owners and travelers.
