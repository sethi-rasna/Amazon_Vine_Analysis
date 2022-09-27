# Amazon Vine Analysis
## Overview

Companies can pay for products to be reviewed by Vine members who are required to test and review the products these companies produce. The purpose of this project is to determine if there is a positive bias for those who review the products through Vine vs. not. 

To conduct this study, PySpark was used to manipulate the data from an AWS S3 bucket and then translated into a AWS RDS database using pgAdmin and SQL.

For this analysis, the "Electronics" category was chosen.

## Results

  - How many Vine reviews and non-Vine reviews were there?
  
  ![comparison_vine_vs_not_percentage](https://user-images.githubusercontent.com/104734224/192642329-c6159cf0-84c4-4f4f-b9f3-5d7e3074db6e.png)

  There were 1080 Vine reviews that received more than 20 votes and the percent of helpful votes were more than 50%. There were 49659 non-Vine reviews. 
  
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  
  454 of the 1080 vine reviews were 5 star reviews. 23034 of the non-vine reviews were 5 star reviews. These are about the same proportion of votes per each category. 

  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  42.03$ of the Vine votes were 5 star reviews; whereas, 46.38% of the non-Vine reviews were 5 star reviews.

## Summary

In conclusion, there was no positive bias from the Vine reviews. For further analysis, it might be worth looking at the total number of reviews to see if there is a bias. 

![total_comparison_vine_vs_not](https://user-images.githubusercontent.com/104734224/192644135-ba9dc1a4-d47d-46e5-ae79-232defbb6cb9.png)

