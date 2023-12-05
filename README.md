# MSBA-2023-BDA-TrendsMktPlace-Team2
# Executive Summary

Every year, the consumer product goods industry witnesses the introduction of around 30,000 new products, yet less than 10% of them manage to achieve true success, as revealed by the McKinsey Consumer Trend Study in 2019. Understanding customers precisely and timely for product development becomes one of the key strengths of consumer packaged goods (CPG) companies. 

Our project's primary objective is to establish a big-data-driven review intelligence and sentiment analysis pipeline, harnessing the capabilities of OpenAI, specifically tailored for the beauty industry. By leveraging LLM, we are able to think naturally again, effortlessly grasping the key information hidden in the data and conveying the business insights efficiently. 

## What is in the pipeline? 
We leverage Databricks, PySpark, and OpenAI APIs to scalably conduct unsupervised analysis of product reviews to extract topics and classify sentiments. By setting up 4 steps of prompts, we process the review data by batches and merge the resulting topics to get a bag of topics on the full scale of data. By labeling each review with topic and sentiment, we are able to generate a comprehensive dashboard of hieriarchical visualizations that is of great use in business settings. 

## What does the pipeline solve? 

By utilizing a prompt-based model in a scalable way, we can easily . With no training required, we are able to conduct review intelligence in a human-like but much more knowledgeable way. By landing on a dashboard that visualizes the topic frequency, distributions of sentiments and topics, and sentiment trends over time, companies can get a comprehensive overview of the customers’ perception of the product. 
