# Amazon Vine Analysis
## Purpose and Overview
Ratings data for luggage purchases on Amazon were analyzed to determine if any bias towards favorable reviews exists for paid members of the Amazon Vine program compared to unpaid reviews.  Two sets of deliverables were requested:

**Deliverable 1-**
Perform ETL on Amazon product reviews by creating four tables/dataframes from the dataset and uploading each as four separate tables into pgAdmin.  The four tables included:
- review_id_table
- products_table
- customers_table
- vine_table

**Deliverable 2-**
Determine bias of Vine reviews by analyzing ratings between paid Vine members and unpaid reviewers. The following questions were addressed:
- How does the number of Vine reviews compare to the number of non-Vine reviews?
- How many Vine and non-Vine reviews were 5-stars?
- What was the percentage of Vine reviews and non-Vine reviews that were 5-stars?

## Resources
- Data Source: amazon_reviews_us_Luggage_v1_00.tsv (Accessed from https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt on 6 April 2022)
- Software and Programming Languages: Spark v.3.0.3; Google Colaboratory; pgAdmin4 v.6.1


## Results
**Deliverable 1-**
- Four tables were created and loaded into pgAdmin4.  Screenshots of each table may be found in the "Resources" folder in this repository.

**Deliverable 2-**
- **Number of Vine reviews vs. non-Vine reviews:**
There were 21 Vine reviews and 6,690 non-Vine reviews for luggage (Figs. 1 and 2).

- **Number of 5-star Vine reviews vs. non-Vine reviews:**
There were 10 5-star Vine reviews and 3,448 5-star non-Vine reviews for luggage (Figs. 1 and 2).

- **Percentage of Vine reviews vs. non-Vine reviews that were 5-stars:**
47.6% of Vine reviews for luggage were 5-star and 51.5% of non-Vine reviews for luggage were 5-star (Figs. 1 and 2).

![vine_paid_analysis](https://user-images.githubusercontent.com/95387273/162474029-d05d890a-c941-4625-a2eb-96a7a002d415.png)

**Fig. 1.** Total number of reviews, number of 5-star reviews, and percentage of 5-star reviews for paid Vine members.

![vine_unpaid_analysis](https://user-images.githubusercontent.com/95387273/162474508-d752b454-65eb-48be-a855-bf528a5b747a.png)

**Fig. 2.** Total number of reviews, number of 5-star reviews, and percentage of 5-star reviews for unpaid reviewers.


## Summary

