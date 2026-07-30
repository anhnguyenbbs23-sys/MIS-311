# MIS-311 

1.Data Overview

1.1 Data Description
     
The Shoe Price dataset includes 202 observations and 4 variables. It provides data on shoe brands, colors, sizes, and prices. The dataset contains both numerical and categorical characteristics, enabling analysis of pricing patterns across different brands and product attributes.

During the data cleaning process, records with missing values and duplicate entries were identified and removed to improve data quality. After cleaning, the final dataset consisted of 196 observations and 4 variables, which were used for the subsequent analysis. (One extreme size outlier of 41 was also flagged for review.)

The major goal of this dataset is to compare shoe prices across brands, colors, and sizes and to uncover potential relationships between these attributes and price. This dataset is suitable for exploratory data analysis because of its relatively clean, organized structure, which can be summarized using descriptive statistics and visualizations.

1.2 Variables

<img width="482" height="198" alt="image" src="https://github.com/user-attachments/assets/fb03a948-c91a-446e-8ed2-3c372d9e6a91" />

2.Data Cleaning
   
Before conducting the analysis, the dataset was examined for data quality issues, including missing values and duplicate records.

2.1 Missing Values

The dataset was examined for missing values with Excel’s COUNTBLANK() function. The two missing values were found across two variables. Specifically, color had one missing value, and price had one missing value. Because the number of missing values was relatively minimal in comparison to the overall dataset, the records were discarded. This method ensured that only full observations were used in the analysis while having a low influence on overall sample size. After eliminating these entries, the dataset included no missing values.

2.2 Duplicate Records

The dataset was checked for duplicate records using Excel’s Remove Duplicates function. A total of three duplicate records were found and eliminated to guarantee that each observation reflected a unique record. The removal of duplicate records enhanced the dataset’s correctness and consistency. After cleaning, the dataset had no duplicate records.

2.3 Outlier Treatment

In addition, one extreme outlier was found in the size column (a value of 41). Since the average shoe sizes in the dataset normally range from 2 to 13, this value is clearly incorrect and was therefore removed to avoid distorting the analysis.

In summary, the data cleaning procedures improved the overall quality of the dataset by removing incomplete, repeated, and unrealistic observations. As a result, the cleaned data (196 observations) are reliable and appropriate for further statistical analysis.

3.Descriptive Statistics

Descriptive statistics were conducted for the two numerical variables, Size and Price, using Excel's Data Analysis ToolPak. The cleaned dataset contains 196 observations.

<img width="452" height="312" alt="image" src="https://github.com/user-attachments/assets/1c088840-47da-4821-ad99-db1cb42ad5ad" />

Analysis

The average shoe size is 7.26, with a median of 7 and a standard deviation of 2.61. The sizes range from 2 to 13, indicating a relatively broad range of shoe sizes. The skewness of -0.13 is close to zero, suggesting that shoe sizes are approximately symmetrically distributed.

The average shoe price is 212.35, with a median of 212 and a standard deviation of 78.89. Prices range from 80 to 350, showing substantial variation among the products. The skewness of 0.02 is very close to zero, indicating that the price distribution is also approximately symmetric rather than strongly skewed.

4.Key Insights 

<img width="602" height="253" alt="image" src="https://github.com/user-attachments/assets/24e70576-6086-4354-9ad2-54afa95d6bc0" />

Insight 1: Shoe prices are widely distributed but approximately balanced.

The histogram and descriptive statistics show that shoe prices range from 80 to 350, with a mean of 212.35 and a median of 212. The near-zero skewness (0.02) indicates that the price distribution is approximately symmetric, suggesting that prices are not heavily concentrated toward either the low or high end.

<img width="600" height="318" alt="image" src="https://github.com/user-attachments/assets/0cd72968-38cc-4e08-b370-ce89e5c83626" />

Insight 2: Average shoe prices differ noticeably across brands.

The Pivot Chart shows clear differences in average shoe prices among the brands, with Reebok recording the highest average price in the dataset. This suggests that brand positioning may influence the price level of shoes and that customers may face different price points depending on the brand they choose.
