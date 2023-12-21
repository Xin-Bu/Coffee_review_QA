# Chat with coffee review text data
### Dataset
The dataset in this project contains two files: coffee_review.pdf and coffee_review.csv. Both are from the same data source. The file coffee_review.pdf has customer review text data only, the basic information of which is shown in the table below. In the coffee_review.csv file, we have 2,095 rows and 12 columns including `name`,`roaster`,`roast`, `loc_country`, `origin_1`, `origin_2`, `100g_USD`, `rating`, `review_date`, `desc_1`, `desc_2`, and `desc_3`. 

| tokens | unique_tokens | avg_token_length | lexical_diversity | top_n | 
| :---:  | :---: | :---: | :---: | :---: | 
| 41,064 | 3,070 | 6.45  | 0.07  | cup;aroma,mouthfeel,acidity,structure,finish,notes,sweet,cocoa,chocolate,syrupy| 

The purpose of this project is to visualize text data in coffee_review.csv using R and to build a platform using python to ask and answer questions from the file coffee_review.pdf. The R code in this project for the visuals was written in R Markdown and knitted to html. 

Here is a wordcloud visual example using R:

![word_cloud](https://github.com/Xin-Bu/LLMs/assets/69817896/799d1cbe-a81d-47b3-8662-c1d73a1e7ccd)

### Data source
[Coffee Reviews](https://www.kaggle.com/datasets/schmoyote/coffee-reviews-dataset/data)

### Reference
Silge, J., & Robinson, D. (2023). *Text mining with R: A tidy approach*. O'Reilly Media, Inc.
