# e-commerce-sales-analysis

The dataset which is used is of an ecommerse website.
The data contain all sales recorded from June to September 2022. Information such as the customers' personal information wasn't included for privacy and confidentiality. Other irrelevant features were also removed to make the dataset simpler and more user-friendly.

# Contents

This dataset contains the following columns along with their descriptions:

order_id: unique identifier for each order placed

order_date: date and time of order
sku: a number used by retailer to assign their products

color: color of the product

size: size of the product, treat missing values as ( One Size )

unit_price: unit price of the product
quantity: quantity ordered for that particular product

revenue: unit_price * quantity

:rocket:Source:https://www.kaggle.com/datasets/shilongzhuang/-women-clothing-ecommerce-sales-data. 

As we started exploring the data we come to know that the data is uncleaned and has so many error, by using various python libraries we are going to cleaned the data and interpreting the hidden insights from the data to support the business growth.

:white_check_mark: Steps we have done in this project

**Exploratory Data Analysis**: Which include understanding the sturcture and behaviour of data

**Data Cleaning**: Removing duplicates, null values, using correct data type, etc. comes under this step.

**Feature Selection and Visualization**: After cleaning the data we have visualized the facts from the data.

## 📦 Python Libraries and Versions

- `pandas==2.2.1`
- `numpy==1.26.4`
- `matplotlib==3.8.4`
- `seaborn==0.13.2`
- `scikit-learn==1.4.2`
