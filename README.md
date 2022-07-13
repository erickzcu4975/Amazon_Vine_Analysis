# Amazon_Vine_Analysis

## Overview of the Analysis:
Analyzing the Tools dataset from Amazons reviews using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, using PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset. Then, a writen summary of the analysis for the SellBy stakeholders.

### Purpose:

Perform ETL on Amazon Product Reviews and Determine Bias of Vine Reviews between vine-reviews and non-vine-reviews within the Amazon review dataset.

## Resources

**Data Source:** [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Tools Review Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz)

**Software:** Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results:

### Total Number of Reviews
<p align="center">
Vine Reviews
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080037-1d509521-cd6c-4ea3-8d82-49b938bafaff.png"> 
</p>
<p align="center">
Non-Vine reviews  
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080042-f963205f-9b62-4b30-aa06-7a33a6bc9389.png"> 
</p>

<br>

### Total Number of 5-Star Reviews
<p align="center">
Vine Reviews
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080032-d1bc108c-8d2e-48e8-b78f-f8526ffe621a.png"> 
</p>
<p align="center">
Non-Vine Reviews  
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080040-ec5f1009-b059-4356-97ae-fef163b05bb6.png"> 
</p>

<br>

### Percentage of 5-Star Reviews
<p align="center">
Vine Percentage Reviews
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080036-7d051aa9-75f1-4378-93e2-830a783ea4ba.png"> 
</p>
<p align="center">
Non-Vine Percentage reviews  
</p>
<p align="center">
    <img src="https://user-images.githubusercontent.com/98966503/173080039-fc8474f8-d802-4caa-b84d-01281f4f96af.png"> 
</p>

<br>

## Summary:

<p align="center">
57% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 46%. This describes a positivity bias for reviews in the Vine program. Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
</p>

