# Chat with coffee review text data

![NCA_Web_Medium_Decaf_1](https://github.com/Xin-Bu/Coming_soon_coffee_review_QA/assets/69817896/de648b89-4169-4257-9355-d00dad94ba86)

[Image source](https://www.ncausa.org/About-Coffee)
### Dataset
The dataset in this project contains two files: coffee_review.pdf and coffee_review.csv. Both are from the same data source. The file coffee_review.pdf has customer review text data only, the basic information of which is shown in the table below. In the coffee_review.csv file, we have 2,095 rows and 12 columns including `name`,`roaster`,`roast`, `loc_country`, `origin_1`, `origin_2`, `100g_USD`, `rating`, `review_date`, `desc_1`, `desc_2`, and `desc_3`. 

| tokens | unique_tokens | avg_token_length | lexical_diversity | top_n | 
| :---:  | :---: | :---: | :---: | :---: | 
| 41,064 | 3,070 | 6.45  | 0.07  | cup;aroma,mouthfeel,acidity,structure,finish,notes,sweet,cocoa,chocolate,syrupy| 

The purpose of this project is to visualize text data in coffee_review.csv using R and to build a platform using python to ask and answer questions from the file coffee_review.pdf. The R code in this project for the visuals was written in R Markdown and knitted to html. 

### Selected text visuals with R
* A wordcloud of the most common words:

![word_cloud](https://github.com/Xin-Bu/LLMs/assets/69817896/799d1cbe-a81d-47b3-8662-c1d73a1e7ccd)

* Term frequency by roast:

![term_frequency](https://github.com/Xin-Bu/Coming_soon_coffee_review_QA/assets/69817896/a8ab25c6-0cf3-45d3-93bb-ad4d65da94d5)

* A world map illustrating the median coffee price by region:
![coffee_price_region](https://github.com/Xin-Bu/Coming_soon_coffee_review_QA/assets/69817896/d40b9487-4d1e-476d-8328-2565baa135d5)

### Procedures of LangChain QA application with Python
* Load documents
* Split documents
* Define embedding
* Create vector database from data
* Define retriever
* Create a chatbot chain
* Create a panel-based interactive dashboard

### Data source
[Coffee Review](https://www.kaggle.com/datasets/schmoyote/coffee-reviews-dataset/data)

### References
Silge, J., & Robinson, D. (2023). *Text mining with R: A tidy approach*. O'Reilly Media, Inc.

[Intro: Deeplearning.ai on Langchain: chat with your data](https://medium.com/theaiengineer/intro-deeplearning-ai-on-langchain-chat-with-your-data-7b4be267d18e)
