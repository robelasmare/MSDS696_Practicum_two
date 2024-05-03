# MSDS696_Practicum_Two
# MSDS Practicum Two
# Book Recommender System Using Neural Network
# Project Objectives and Problem Definition
Currently, we live in an era where different aspects of our lives are dominated by artificial intelligence (AI). Businesses that implement AI in their decision-making processes experience improved results. One type of artificial intelligence application is recommendation systems. The recommendation system provides personalized recommendations for users by analyzing patterns in their behavior as well as patterns in similar users. Its implication in business results in improved customer retention and engagement, which increases product sales. For instance, in 2011-2012, when Amazon first deployed its collaborative filtering-based recommender system, it recorded a 29% increase in sales by the second fiscal quarter of 2012. Today, recommendation engines are used in various sectors such as e-commerce, movie streaming services, social media services, health, and fitness, and more. The recommendation system market is predicted to increase from 2.12 billion US dollars in 2020 to 15.3 billion US dollars by 2026.Recognizing the benefits of recommendation systems, this project aims to develop a collaborative book recommendation system to provide personalized book suggestions based on users' rating inputs. This keeps users engaged, maximizes retention and user satisfaction, and increases revenue. References: Ahramovich, A. (n.d.). Recommendation Systems and Machine Learning. Recommendation Systems and Machine Learning. https://www.itransition.com/machine-learning/recommendation-systems

# Project Details
To analyze the data, we use Jupyter Notebook with Python 3 to interact with and analyze the data. Due to the computational load, we utilize Google Colab. We employ data understanding methods to comprehend and combine each dataset. Exploratory Data Analysis (EDA) is performed to gain insights about the datasets. Data preprocessing techniques are applied for data cleaning, handling missing values, feature engineering, and normalizing the rating values.

In this paper, we use collaborative filtering methods employing a neural network architecture called matrix factorization to make recommendations by identifying the interactions between users and books and learning the preferences of the users based on their ratings. Using the learned interactions, the model is trained to predict ratings based on the captured interactions of users and books. Then, the model will be used to generate recommendations.

Since the aim is to predict the rating of books for users based on the captured patterns of user IDs and book IDs, it is a regression-type model. Due to the nature of the data, considering factors such as rating scale and outliers, we use Mean Absolute Error (MAE) for evaluating the developed models. In this paper, three models are developed, and the model that produces the lowest MAE is selected for recommendation of books for users.

# Datasets Sources
First dataset obtained from https://github.com/zygmuntz/goodbooks-10k
Second dataset is obtained from https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews?select=Books_rating.csv.
The third dataset is collected from https://www.kaggle.com/code/mehmetcanduru/hybrid-book-recommendation-user-and-tem-based/notebook
