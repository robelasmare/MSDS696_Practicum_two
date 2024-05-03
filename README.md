# MSDS696_Practicum_Two
## Book Recommender System Using Neural Network
### Project Objectives and Problem Definition

Currently, we live in an era where different aspects of our lives are dominated by artificial intelligence (AI). Businesses that implement AI in their decision-making processes experience improved results. One type of artificial intelligence application is recommendation systems.

The recommendation system provides personalized recommendations for users by analyzing patterns in their behavior as well as patterns in similar users. Its implication in business results in improved customer retention and engagement, which increases product sales. For instance, in 2011-2012, when Amazon first deployed its collaborative filtering-based recommender system, it recorded a 29% increase in sales by the second fiscal quarter of 2012. Today, recommendation engines are used in various sectors such as e-commerce, movie streaming services, social media services, health, and fitness, and more. The recommendation system market is predicted to increase from 2.12  billion US dollars  in 2020 to 15.3 billion US dollars by 2026. Recognizing the benefits of recommendation systems, this project aims to create a neural-based collaborative book recommendation system. The goal is to offer personalized book suggestions. The system uses a collaborative filtering-based neural network to predict how users rate books they haven't read. By understanding patterns in users' preferences and book characteristics, the system suggests highly rated books tailored to each user's tastes and experiences.

### References:
Ahramovich, A. (n.d.). Recommendation Systems and Machine Learning. Recommendation Systems and Machine Learning. https://www.itransition.com/machine-learning/recommendation-systems

## Project Details
For data analysis, we leverage Jupyter Notebook with Python 3, utilizing Google Colab to manage computational loads efficiently. Employing data understanding techniques, we comprehensively merge and analyze each dataset. Exploratory Data Analysis (EDA) offers valuable insights into the datasets. We employ various data preprocessing techniques for cleaning, handling missing values, feature engineering, and normalizing rating values.

In this study, collaborative filtering methods, employing a neural network architecture, are utilized for making recommendations. This involves identifying interactions between users and books, learning user preferences based on their ratings, and training the model to predict ratings from captured interactions. Subsequently, the trained model is utilized to generate recommendations.

Given the objective of predicting book ratings for users based on user and book ID patterns, our approach entails a regression-type model. To evaluate model performance, we employ Mean Absolute Error (MAE), considering factors such as rating distribution and outliers in the dataset. We develop three models, selecting the one with the lowest MAE for generating book recommendations for users.

## Datasets Sources
1. First dataset obtained from  https://github.com/zygmuntz/goodbooks-10k
2. The second dataset is obtained from  https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews?select=Books_rating.csv.
3. The third dataset is collected from https://www.kaggle.com/code/mehmetcanduru/hybrid-book-recommendation-user-and-tem-based/notebook
