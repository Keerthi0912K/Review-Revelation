# Review Revelation
**Review Revelation** is a sentiment analysis project designed to uncover insights from hotel reviews. The primary goal is to analyze these reviews to gain a deeper understanding of customer experiences, helping hotel management identify their strengths and areas for improvement.


## Project Overview
In this project, I analyze hotel reviews using sentiment analysis techniques. By examining the sentiment expressed in the reviews, I aim to provide actionable insights to help hotel management enhance their services and facilities. The project focuses on identifying positive and negative aspects of the hotel experience and understanding how customer sentiment evolves over time.


## Features
- **Sentiment Analysis**: I determine the overall sentiment of customer reviews, classifying them as positive, negative, or neutral.
- **Text Preprocessing**: I clean and preprocess the review text by removing unnecessary words and phrases, such as "Read more" and "Read less," to ensure that the analysis focuses on the core content of the reviews.
- **Word Cloud Visualization**:  I create word clouds for positive and negative reviews, visualizing the most common terms and sentiments customers mention.
- **Sentiment Distribution Analysis**: I analyze and visualize the distribution of sentiment scores across all reviews, helping to identify patterns and trends.
- **Temporal Sentiment Analysis**: I examine how customer sentiment changes, identifying trends and potential seasonal patterns that could affect guest experiences.


## Usage

### Preprocess the Data
1. I load the hotel reviews dataset.
2. I clean the data by removing unnecessary text such as "Read more" and "Read less."
3. I perform text preprocessing, including tokenization, removal of stopwords, and stemming, to prepare the data for sentiment analysis.

### Perform Sentiment Analysis
1. I calculate sentiment scores for each review using natural language processing techniques.
2. Based on these sentiment scores, I classify the reviews into positive, negative, or neutral categories.

### Generate Insights
I create word clouds to visualize the most frequently mentioned words in positive and negative reviews.
I visualize the distribution of sentiment scores to identify overall trends and outliers.
I analyze sentiment trends over time to identify any fluctuations or seasonal patterns.


## Example Output ![image](https://github.com/user-attachments/assets/bb7664c4-65bf-470a-a573-3fc16cc4fc94)


### Word Clouds
- The word clouds reveal frequently mentioned words in positive and negative reviews. For instance, in positive reviews, terms like "nicely," "elegant," "loved," "well," and "helpful" stand out. At the same time, the word "dirty" is prominent in negative reviews.

![image](https://github.com/user-attachments/assets/25deca08-7178-430f-9d63-2ad174868c63)

![image](https://github.com/user-attachments/assets/61fb1277-54ff-432a-99f0-909dce4113e6)

### Sentiment Distribution
The sentiment distribution analysis shows that most reviews are clustered around a neutral to slightly positive sentiment score, with a few reviews expressing extreme sentiments.

![image](https://github.com/user-attachments/assets/a6b7587e-99d3-49d5-b640-2cba213598d5)

### Sentiment Over Time
The sentiment analysis over time reveals fluctuations, with noticeable dips in March 2019 and peaks in December 2018, suggesting that specific periods may influence customer experiences.

![image](https://github.com/user-attachments/assets/5bbb1bda-d152-4873-9159-6c8ad9d5fcd8)

### Impact of Location
Locations such as Ireland, Fairfax Station, VA, and Mexico have high average sentiment scores, indicating positive guest experiences. In contrast, places like China, Modesto, CA, and Pikeville, KY, have lower sentiment scores, highlighting areas needing improvement.

![image](https://github.com/user-attachments/assets/7d1e1a88-2e49-412b-96e4-10bcf782a08c)


## Insights and Implications

### Top Positive Attributes
- **Common Positive Words**: The frequent positive terms suggest that customers appreciate the hotel's ambiance, cleanliness, staff behavior, and overall comfort. Positive experiences are linked to the quality of service and the environment.

### Top Negative Attributes
- **Common Negative Word**: The word "dirty" in negative reviews indicates that cleanliness is a significant concern. Maintaining a clean environment improves guest satisfaction and reduces negative feedback.

### Sentiment Distribution Observations
- The clustering of reviews around a neutral to slightly positive sentiment score indicates that while many guests had a generally positive experience, some outliers point to highly positive or negative experiences. Addressing the issues raised in the negative outliers could further enhance overall guest satisfaction.

### Sentiment Over Time Observations
- The fluctuations in sentiment over time suggest that seasonal factors or specific events could influence guest experiences. For example, positive reviews during holiday seasons may reflect festive experiences, while dips in sentiment indicate periods where the hotel needs to address specific issues.

### Impact of Location Observations
- The sentiment analysis by location shows that some places have higher average sentiment scores, likely due to better facilities or service quality. In comparison, others have lower scores, indicating areas for improvement.


## Actionable Steps
- **Improve Cleanliness**: Stricter cleaning protocols could address the cleanliness concerns highlighted in the negative reviews, improving guest satisfaction.
- **Staff Training**: Positive feedback regarding staff behavior emphasizes the importance of continuous training and staff recognition to maintain and enhance service quality.
- **Monitor Seasonal Trends**: Analyzing sentiment trends over time can help the hotel prepare for high and low periods. Ensuring extra staff and services during peak seasons can help maintain high satisfaction levels.
- **Location-Specific Improvements**: Tailoring improvements to specific locations based on sentiment analysis can address unique challenges and enhance guest experiences where they are most needed.
- **Continuous Feedback Loop**: Regularly collecting and analyzing guest feedback can help the hotel promptly address emerging issues and reinforce positive aspects, leading to consistently high levels of guest satisfaction.


By focusing on these actionable steps, the hotel can enhance the guest experience and increase positive feedback in future reviews.
