# Amazon_Vine_Analysis

## Overview

In this project I intend to see if there is any bias toward reviews that were written as part of the Amazon Vine program. This program gives the members vendor products at no charge in return for their reviews on those roducts. Here I accomplished a bias assessment for a specific product category, Books. In doing so, first, I extract book reviews data from Amazon AWS S3. Then, using PySpark, I create dataframes that allow me to count the number of paid and unpaid reviews as well as filter out five star reviews. Based on the obtained dataframes, finally, I will calcualte the percentage of five star reviews allowing for bias assessment.

## Results

