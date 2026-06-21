<div align="center">

<img src="https://img.shields.io/badge/End--To--End--Recommendation--System-8A2BE2?style=for-the-badge&labelColor=000000" />

</div>
<img width="1408" height="714" alt="Gemini_Generated_Image_z8afjcz8afjcz8af" src="https://github.com/user-attachments/assets/f5018d6c-0a0c-45fb-94d0-cfe07b6377fa" />


## Introduction
The Anime Ratings Analysis & Recommender System is a Data Science project designed to analyze anime rating patterns and develop a recommendation engine that suggests anime based on user preferences.

The project combines Exploratory Data Analysis (EDA) with Recommendation System techniques to uncover insights from anime ratings data and provide personalized anime recommendations.

## About Dataset
The dataset contains information on 12,294 anime titles with 7 features. It includes details such as anime_id, name, genre, type, episodes, rating, and members. The dataset provides information about different anime series and movies, including their genres, formats, episode counts, user ratings, and community popularity, making it suitable for exploratory data analysis, recommendation systems, popularity prediction, and audience preference analysis projects.

## EDA
Conducted an in-depth analysis of the anime dataset to understand the distribution of ratings, popularity, genres, and user engagement patterns. Initial exploration involved examining dataset dimensions, data types, missing values, and duplicate records to ensure data quality and consistency before further analysis.
Analyzed the distribution of anime ratings to identify overall user sentiment and determine whether users tend to rate anime positively or negatively. Statistical summaries and visualizations were used to understand rating trends and detect potential outliers.
Investigated the most popular and highest-rated anime titles by comparing average ratings and member counts. This helped identify anime that not only received strong ratings but also attracted significant audience engagement.
Performed genre-wise analysis to understand audience preferences across different anime categories. Visualizations highlighted the genres with the highest popularity and average ratings, providing insights into viewer interests.
Explored user rating behavior by examining rating frequency and participation levels. This analysis helped identify active users, rating patterns, and the overall structure of user engagement within the platform.
Created visual representations using Matplotlib and Seaborn, including histograms, bar charts, and distribution plots, to effectively communicate insights and support the development of the recommendation system.

## ML Model
Collaborative Filtering: Implemented collaborative filtering techniques to generate recommendations based on user rating behavior. The model identifies similarities between anime titles by analyzing patterns in user preferences and interactions.
Cosine Similarity: Utilized Cosine Similarity to measure the similarity between anime vectors within the user-anime interaction matrix. Anime with higher similarity scores are recommended to users based on their viewing history and preferences.
K-Nearest Neighbors (KNN) for Recommendation: Applied KNN-based recommendation logic to identify the most similar anime titles and generate personalized recommendations. This approach helps discover anime that share similar rating patterns among users.
User-Anime Interaction Matrix: Constructed a sparse matrix representing user ratings for anime titles, serving as the foundation for similarity calculations and recommendation generation.
Recommendation Engine: Combined similarity-based techniques and user preference analysis to create an efficient recommendation system capable of suggesting relevant anime titles based on historical user ratings.

## Model Evaluation
The recommendation system was evaluated by analyzing the relevance and similarity of the anime titles suggested to users. Recommendations generated through Collaborative Filtering and Cosine Similarity were manually validated to ensure that the suggested anime shared comparable genres, themes, and user rating patterns with the selected anime.
Similarity scores were examined to measure how closely related the recommended anime were to the input title. Higher similarity values indicated stronger relationships between anime, resulting in more accurate and meaningful recommendations.
The user-anime interaction matrix was assessed to verify that user preferences were effectively captured and utilized during recommendation generation. This ensured that the model leveraged historical rating behavior to identify hidden patterns and viewing preferences.
Recommendation quality was further evaluated by testing multiple anime titles across different genres and comparing the suggested results with known popular and related anime. The generated recommendations demonstrated strong consistency and relevance, indicating that the model successfully identified similar anime based on user rating trends.
Overall, the recommendation engine achieved effective performance in delivering personalized and relevant anime suggestions, showcasing the practical application of similarity-based recommendation techniques in entertainment and content recommendation systems.

## Recommendation System
The recommendation engine suggests anime based on user interests and similarity patterns.
Methodology
Create User-Anime Interaction Matrix
Compute Similarity Scores
Identify Similar Anime
Generate Recommendations
Return Top-N Anime Suggestions
Features
Personalized Recommendations
Similar Anime Discovery
User Preference-Based Suggestions
Scalable Recommendation Framework

## Deployment
The Anime Recommendation System was successfully deployed as a web application using GitHub Pages, enabling users to access the project through a browser without requiring any local installation or configuration. The deployment provides an intuitive and responsive interface for exploring the recommendation system, project workflow, and analytical insights generated from the anime ratings dataset.
The deployed application showcases the complete end-to-end implementation of the project, including data preprocessing, exploratory data analysis, recommendation engine development, and result visualization. It allows users to interact with the system and understand how recommendations are generated based on user preferences and similarity measures.
GitHub Pages was utilized as the hosting platform to ensure seamless accessibility, fast loading times, and easy maintenance. The deployment demonstrates the practical integration of data science, machine learning, and web technologies to transform a notebook-based project into a publicly accessible portfolio application.
Live Project Link: https://sunidhihere.github.io/End-To-End-Recommendation-System/

## Key Insights
Certain anime genres consistently receive higher ratings.
Popular anime attract significantly larger user engagement.
User preferences exhibit clear viewing patterns.
Recommendation systems effectively identify similar anime titles.
## Results
The developed recommendation system successfully generates relevant anime recommendations by leveraging user rating behavior and anime similarity metrics.

The project demonstrates the practical application of data preprocessing, exploratory data analysis, feature engineering, and recommendation system development in a real-world entertainment dataset.
