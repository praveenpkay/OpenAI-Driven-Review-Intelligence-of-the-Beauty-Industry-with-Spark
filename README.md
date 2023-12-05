# MSBA-2023-BDA-TrendsMktPlace-Team2
# Executive Summary

Every year, the consumer product goods industry witnesses the introduction of around 30,000 new products, yet less than 10% of them manage to achieve true success, as revealed by the McKinsey Consumer Trend Study in 2019. Understanding customers precisely and timely for product development becomes one of the key strengths of consumer packaged goods (CPG) companies. 

Our project's primary objective is to establish a big-data-driven review intelligence and sentiment analysis pipeline, harnessing the capabilities of OpenAI, specifically tailored for the beauty industry. By leveraging LLM, we are able to think naturally again, effortlessly grasping the key information hidden in the data and conveying the business insights efficiently. 

## What is in the pipeline? 
We leverage Databricks, PySpark, and OpenAI APIs to scalably conduct unsupervised analysis of product reviews to extract topics and classify sentiments. By setting up 4 steps of prompts, we process the review data by batches and merge the resulting topics to get a bag of topics on the full scale of data. By labeling each review with topic and sentiment, we are able to generate a comprehensive dashboard of hieriarchical visualizations that is of great use in business settings. 

![alt text](https://github.com/Xingyue-Wang47/MSBA-2023-BDA-TrendsMktPlace-Team2/blob/main/Pipeline%20Flowchart)

## What does the pipeline solve? 
### Resolves the token limit of OpenAI prompt input and is able to handle large size of contents and generate topics on full scale of data. 
### Generates nearly completely unsupervised topics results with no number of topics specified. 
### Distinguished from traditional LDA by identifying topics based on its LLM training experience, not on the current dataset alone. 
### Provides a more flexible sentiment analysis option, in which specific customized interest in sentiments can be analyzed easily (e.g. label the reviews that favor the color of this product as "positive in color")

5. The pipeline can be easily extended to many industries, as long as there is available review data
6. The pipeline leads to a comprehensive dashboard that provides analysis on different levels
By utilizing a prompt-based model in a scalable way, we can easily . With no training required, we are able to conduct review intelligence in a human-like but much more knowledgeable way. By landing on a dashboard that visualizes the topic frequency, distributions of sentiments and topics, and sentiment trends over time, companies can get a comprehensive overview of the customers’ perception of the product. 
