# Customer Behaviour Analysis using Spark

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products
This project leverages big data techniques to perform a comprehensive analysis of customer behavior. The analysis includes data cleaning, visualization, and extraction of business insights to support strategic decision-making in marketing, inventory management, and customer retention.The main feature of this project is the use of multidimensional scaling to analyze regional product category preferences.

## Table of Contents

1. [Dataset Description](#dataset-description)
2. [Installation](#installation)
3. [Features](#features)
4. [Contributing](#contributing)
5. [License](#license)
6. [Contact Information](#contact-information)

## Dataset Description

The dataset consists of the following columns:

- **User_ID**: Unique identifier for each user.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the user (F for female, M for male).
- **Age**: Age group of the user (e.g., 0-17, 18-25, etc.).
- **Occupation**: Occupation code for the user.
- **City_Category**: Category of the city (A, B, C).
- **Stay_In_Current_City_Years**: Number of years the user has stayed in the current city.
- **Marital_Status**: Marital status of the user (0 for single, 1 for married).
- **Product_Category_1**: Category of the product.
- **Product_Category_2**: Category of the product where the product may also be a part of.
- **Product_Category_3**: Category of the product where the product may also be a part of.
- **Purchase**: Purchase amount.

## Installation

## Insights

1. **Data Cleaning and Visualization**:

   - Performed missing value imputation, removed duplicates, detected and handled outliers, and normalized the data.
   - Conducted data visualizations to uncover patterns and trends.

2. **Average Purchase Amount by Product Category**:

   - **Usefulness**: Identifies which product categories generate the highest revenue on average.
   - **Importance**: Helps prioritize inventory management and marketing efforts towards high-value categories, optimizing stock levels, and creating targeted promotions.

3. **Analysis of Product Popularity Across Different Age Groups**:

   - **Usefulness**: Determines which products are most popular among different age groups.
   - **Importance**: Enables targeted marketing and personalized product recommendations based on age demographics, improving customer satisfaction and sales.

4. **Product Performance and Inventory Management**:

   - **Usefulness**: Assesses the sales performance of individual products.
   - **Importance**: Identifies top-performing and underperforming products, optimizing inventory levels, reducing overstock and stockouts, and making informed procurement decisions.

5. **Customer Lifetime Value (CLTV) Analysis**:

   - **Usefulness**: Calculates the total value a customer brings over their lifetime.
   - **Importance**: Identifies high-value customers, focuses retention efforts on them, optimizes marketing spend, and tailors loyalty programs to maximize long-term profitability.

6. **Customer Retention and Loyalty Analysis**:

   - **Usefulness**: Analyzes the purchasing behavior of repeat customers.
   - **Importance**: Identifies loyal customers, understands retention patterns, and supports the development of strategies to increase customer loyalty, such as personalized offers and rewards programs.

7. **Analysis of Product Category Combinations**:

   - **Usefulness**: Identifies which product categories are frequently bought together.
   - **Importance**: Enhances cross-selling and upselling strategies, optimizes product placement and bundling in stores or online, and increases the average order value.

8. **Gender-Based Product Category Analysis**:

   - **Usefulness**: Examines purchasing patterns based on gender.
   - **Importance**: Provides insights into gender-specific preferences, supports the creation of targeted marketing campaigns, and helps in tailoring product assortments to meet the preferences of different gender demographics.

9. **Multidimensional Scaling for Regional Product Category Analysis**:
   - **Usefulness**: Visualizes regional customer demographics and preferences, aiding in tailored marketing and inventory management based on unique product category insights.
   - **Importance**: Supports strategic decision-making and resource allocation by identifying regional market trends and high-performing product categories, and aids in effective planogram development for optimal product placement.

## Contributing

Contributions are always welcome!

Please see `contributing.md` for ways to get started.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact Information

- **Kizhakkeppattu Rahul Govindkumar**
- **Email**: krahulgovind@gmail.com
- **Github**: https://github.com/rahulorihiki
