Data Sampling and Exploration using Pandas (Google Colab)
Project Overview

This project demonstrates data exploration and random sampling techniques using Python in Google Colab. The dataset used contains transactional information such as orders, shipping details, customer segments, locations, and product categories.

The notebook focuses on understanding the dataset structure and creating a reproducible random sample for further analysis.

View Notebook

Open in Google Colab

Dataset Description

The dataset consists of 9994 rows and 14 columns and includes the following features:

Serial ID

Order ID

Order Date & Ship Date

Ship Mode

Business Segment (Consumer, Corporate, etc.)

City, State, Region

Product Category & Sub-Category

Cost Per Unit

Price Per Unit

This dataset is suitable for sales analysis, customer segmentation, and business insights.

Key Operations Performed
1️⃣ Data Exploration

Checked the size of the dataset using:

ak_60_df.shape

Output: (9994, 14)

2️⃣ Random Sampling

Created a unique random sample of 2001 records:

ak_60_df_unique_sample = ak_60_df.sample(n=2001, random_state=42)

Ensures reproducibility using random_state.

3️⃣ Data Preview

Displayed the first few rows of the sampled dataset:

ak_60_df_unique_sample.head()
4️⃣ Validation

Confirmed the sample size:

ak_60_df_unique_sample.shape
Objectives

Understand dataset structure and dimensions

Perform random sampling for analysis

Prepare data for further analytics or machine learning tasks

Ensure consistent and reproducible results

Technologies Used

Python

Pandas

Google Colab

How to Use

Open the notebook using the Colab link above

Run all cells using Runtime → Run All

Modify sampling size or parameters as needed

Use the sampled dataset for further analysis

Future Improvements

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Data visualization (Matplotlib / Seaborn)

Machine learning model implementation

👨‍💻 Author

Your Name: Awantika Kholia

Acknowledgements

This project is part of academic practice for learning data analysis and sampling techniques using Python.
