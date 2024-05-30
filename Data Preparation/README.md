## About Data Preparation and Transformation
In this document, I have conducted a comprehensive data processing procedure to refine the transactional data available in the main dataset. The dataset comprises transactional records containing the timestamps and dates of the transaction.

To optimize data analysis and facilitate insights extraction, I have restructured the data to represent each day's sales in a structured manner. Specifically, I have transformed the data to generate three distinct rows for each day, delineating sales patterns across different times of the day.

The transformation entails the following structure:

Morning Sales (First Row): This row encapsulates the sales figures during the morning hours.
Afternoon Sales (Second Row): The second row provides insights during the afternoon period.
Night Sales (Third Row): The third row presents data during the night, including aggregated information such as total sales and total quantity sold.
So as an illustration, consider a dataset spanning approximately 90 days (3 months). By applying the aforementioned data transformation methodology, the resulting dataset would contain a total of 90*3 = 270 rows approx, each offering granular insights into supermart sales dynamics across various times of the day.

For the Reference Here is the orginal dataset link: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales
