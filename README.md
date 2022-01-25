# Amazon_Vine_Analysis
## Overview of the analysis  
The project is about analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
So for this project we worked doing ETL again. This time we worked with Amazon´s AWS. We created a RDS Database, connected to PgAdmin and we pulled the information from a bucket that amazon gives out. Using Pyspark we completed this ETL process:  


## Results

How many Vine reviews and non-Vine reviews were there?
- **Vine reviews**: 94 
- **Non-Vine reviews**: 40471  
  
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  
- **5 start Vine reviews**: 48 
- **5 star Non-Vine reviews**: 15663  
  
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?  
- **Percentage 5 star Vine reviews**: 51.06% 
- **Percentage 5 star Non-Vine reviews**: 38.71%  

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.


