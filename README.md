# Amazon_Vine_Analysis

## Overview

In this project I intend to see if there is any bias toward reviews that were written as part of the Amazon Vine program. This program gives the members vendor products at no charge in return for their reviews on those roducts. Here I accomplished a bias assessment for a specific product category, Books. In doing so, first, I extract book reviews data from Amazon AWS S3. Then, using PySpark in Google CoLab environment, I create dataframes that allow me to count the number of paid and unpaid reviews as well as filter out five star reviews. Based on the obtained dataframes, finally, I will calcualte the percentage of five star reviews allowing for bias assessment.

## Results

Below are the screenshots of the results I obtained through the process explained in the Overview section.

![This is an image](/Paid_Reviews.png) ![This is an image](/Unpaid_Reviews.png) 

As it can be seen, as part of this dataset, 4987 reviews were posted by Vine program members, 2029 of which rated the product as 5 star. On the other hand, among the 108015 reviews submitted by non-Vine members, 49645 reviews gave a 5 star to the product. Overall, 40.69% and 45.96% of the reviews submitted by Vine and non-Vine members, respectively, rated the product with a 5 star.

## Summary

