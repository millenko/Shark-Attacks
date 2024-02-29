![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# QUEST | Sharks Attacks

<br>

## Introduction

Welcome to the Shark Attacks!
<br>
In this project, we will share with you information about global shark attack reports, demonstrate our newly acquired data wrangling and analysis techniques.
<br>
Then, hopefully, you will share with us some admiration for the job well-done, as well as other, constructive feedback.
<br>

For a while, our motivation for the project was to get a passing grade, until we remembered that Ironhack is not that kind of school.
<br>
After that, our motives became less ulterior and more altruistic, which is to determine what and how much have we learned so far, and to continue the learning.
<br>
We hope to be a contributing factor to decrease in the shark-related accidents, for the sake of both humans and sharks.

## Team members
- Deimante Piraityte
- Oğuzhan Şahingöz
- Sophiya Siddiqui
- Milenko Rosić

## Installation & setup
- Fork this repo
- Clone it to your machine

### Required environment
- Jupyter Notebook
- Python is 3.11.5 or higher
- Numpy
- Pandas
- Matplotlib
- RE
- Pickle

## About the dataset
The dataset used in this analysis is [GSAF Incident Log](https://www.sharkattackfile.net/incidentlog.htm).
<br>
The mission of the Global Shark Attack File is to provide current and historical data on shark/human interactions for those who seek accurate and meaningful information and verifiable references.
<br>
It is the goal of the Global Shark Attack File to demonstrate and emphasize, through forensic analysis, the significance of shark/human interactions in comparison to the myriad dangers that we face in our daily lives.
<br>
[The original dataset](https://www.sharkattackfile.net/spreadsheets/GSAF5.xls) is in .xls Excel file format, loaded into a Jupyter Notebook for analysis in Python.

### Problem statement
Shark attack reports seem to be increasing over the past years.

### Hypothesis
An escalation in oceanic activities, such as surfing and swimming, will correlate with an increase in shark attacks along coastal regions of the USA.
<br>

### Understanding the data
We used Pandas built-in functions such as describe, head, info, unique, to familiarize ourselves with the data.
<br>
The original dataset consist of 6965 rows over 23 columns.
<br>
Though it was a promising number that the dataset is well-fulfilled, the dataset proved to be rather dirty.
<br>

### Formatting
We used Pandas built-in functions to format the data, to reach clarity and needs of our analysis.
<br>
The dataset was reduced to 1592 rows over 7 columns:
<br>

### Data Description
- Customer: Customer ID.

- ST: State where customers live.

- Gender: Gender of the customer.

- Education: Background education of customers.

- Customer Lifetime Value: Customer Lifetime Value (CLV) is the total revenue the client will derive from their entire relationship with a customer. In other words, it is the predicted or calculated value of a customer over their entire duration as a policyholder with the insurance company. It is an estimation of the net profit that the insurance company expects to generate from a customer throughout their relationship with the company. CLV takes into account factors such as the duration of the customer's policy, premium payments, claim history, renewal likelihood, and potential additional services or products the customer may purchase. It helps insurers assess the long-term profitability and value associated with retaining a particular customer.

- Income: Customer's earnings.

- Monthly Premium Auto: The monthly premium amount a customer pays for their auto insurance. It represents the recurring cost that the insured person must pay to maintain their insurance policy and receive coverage for potential damages, accidents, or other covered events related to their vehicle.

- Number of Open Complaints: Number of complaints the customer has opened.

- Policy Type: Insurance policy categories include Corporate Auto, Personal Auto, and Special Auto.

- Vehicle Class: Specifies the class of insured vehicles, such as Two-Door Car, Four-Door Car SUV, Luxury SUV, Sports Car, and Luxury Car.

- Total Claim Amount: The sum of all claims made by the customer. It represents the total monetary value of all approved claims for incidents such as accidents, theft, vandalism, or other covered events.
<br>

### Data-quality points
- The column-names had consistent appearance.
- The values had inconsistent appearance with regards to leading and trailing whitespace, use of the capital letters and abbreviations.
  - These have been corrected by stripping the whitespace, and with functions and methods such as : lambda, applymap, title, .replace.
- "Year" column has been converted to integers, with astype method.
- "Sex" column values have been reduced from multiple unique values to 2: M and F.
there are columns which appear almost empty or mostly populated by missing or useless data.


### Under the hood
- Data structures used: lists, dictionaries, sets
- Flow control: if-else statements
- Functions: mostly Pandas built-in functions and methods
- 

### Acknowledgements
GSAF Field Investigators
Don Nacho
Simi
