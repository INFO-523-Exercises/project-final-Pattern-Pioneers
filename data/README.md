# Data

This is a dataset collected for analyzing the behavioral analysis of Amazon's consumers consists of a comprehensive collection of customer interactions,browsing patterns within the Amazon ecosystem. It includes a wide range of variables such as customer demographics, user interaction, and reviews. The dataset aims to provide insights into customer preferences, shopping habits, and decision-making processes on the Amazon platform. By analyzing this dataset, researchers and analysts can gain a deeper understanding of consumer behavior, identify trends, optimize marketing strategies, and improve the overall customer experience on Amazon.

# Codebook for the Dataset

```{r}
# GETTING THE LIBRARIES
if (!require(pacman))
  install.packages(pacman)


pacman::p_load(here)
               
data <- read_csv(here("data", "Amazon_Customer_Behavior_Survey.csv"))

```

## Variable Names and Descriptions:

-   age --- age
-   gender --- gender
-   Purchase_Frequency --- How frequently do you make purchases on Amazon?
-   Purchase_Categories --- What product categories do you typically purchase on Amazon?
-   Personalized_Recommendation_Frequency --- Have you ever made a purchase based on personalized product recommendations from Amazon?
-   Browsing_Frequency --- How often do you browse Amazon's website or app?
-   Product_Search_Method --- How do you search for products on Amazon?
-   Search_Result_Exploration --- Do you tend to explore multiple pages of search results or focus on the first page?
-   Customer_Reviews_Importance --- How important are customer reviews in your decision-making process?
-   Add_to_Cart_Browsing --- Do you add products to your cart while browsing on Amazon?
-   Cart_Completion_Frequency --- How often do you complete the purchase after adding products to your cart?
-   Cart_Abandonment_Factors --- What factors influence your decision to abandon a purchase in your cart?
-   Saveforlater_Frequency --- Do you use Amazon's "Save for Later" feature, and if so, how often?
-   Review_Left --- Have you ever left a product review on Amazon?
-   Review_Reliability --- How much do you rely on product reviews when making a purchase?
-   Review_Helpfulness --- Do you find helpful information from other customers' reviews?
-   Personalized_Recommendation_Frequency --- How often do you receive personalized product recommendations from Amazon?
-   Recommendation_Helpfulness --- Do you find the recommendations helpful?
-   Rating_Accuracy --- How would you rate the relevance and accuracy of the recommendations you receive
-   Shopping_Satisfaction --- How satisfied are you with your overall shopping experience on Amazon?
-   Service_Appreciation --- What aspects of Amazon's services do you appreciate the most?
-   Improvement_Areas --- Are there any areas where you think Amazon can improve?

## Data Types:

-   age --- double
-   gender --- character
-   Purchase_Frequency --- character
-   Purchase_Categories --- character
-   Personalized_Recommendation_Frequency --- character
-   Browsing_Frequency --- character
-   Product_Search_Method --- character
-   Search_Result_Exploration --- character
-   Customer_Reviews_Importance --- double
-   Add_to_Cart_Browsing --- character
-   Cart_Completion_Frequency --- character
-   Cart_Abandonment_Factors --- character
-   Saveforlater_Frequency --- character
-   Review_Left --- character
-   Review_Reliability --- character
-   Review_Helpfulness --- character
-   Personalized_Recommendation_Frequency --- double
-   Recommendation_Helpfulness --- character
-   Rating_Accuracy --- double
-   Shopping_Satisfaction --- character
-   Service_Appreciation --- character
-   Improvement_Areas --- character
