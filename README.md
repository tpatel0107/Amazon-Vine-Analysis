# Amazon-Vine-Analysis
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.
## Resources
**Data Source: Amazon Review datasets, Video Games Review dataset
**Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS
## Results

##Vine Reviews

*Total number of reviews

![GitHub Graph](https://github.com/tpatel0107/Amazon-Vine-Analysis/blob/main/Total%20Number%20of%20Reviews.PNG?raw=true)

*Vine reviews

![GitHub Graph](https://github.com/tpatel0107/Amazon-Vine-Analysis/blob/main/Vine%20review%20Yes.PNG?raw=true)

*Non Vine Reviews

![GitHub Graph](https://github.com/tpatel0107/Amazon-Vine-Analysis/blob/main/Vine%20review%20No.PNG?raw=true)




*Vine Reviews 5 star

![GitHub Graph](https://github.com/tpatel0107/Amazon-Vine-Analysis/blob/main/Total%20number%20of%20vine%20reviews.PNG?raw=true)

*Vine reviews non 5 star

![GitHub Graph](https://github.com/tpatel0107/Amazon-Vine-Analysis/blob/main/total%20number%20of%20vine%20reviews2.PNG?raw=true)


##Summary
49.64% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 37.34%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.


