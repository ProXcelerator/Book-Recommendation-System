
# Project Overview: Manga Recommendation System
## Domain and Scope
This project explores the domain of personalized manga recommendations, aiming to enhance
user experience by providing tailored suggestions. By leveraging user preferences, manga
metadata, and advanced machine learning algorithms, the system ensures relevance and
accuracy in recommendations. The primary goal is to deliver a platform that aligns closely with
users' tastes and expands their discovery of new manga.
## Data Utilized
The system integrates two main datasets:
1. Manga Metadata: Extracted from publicly available sources, including titles, genres,
themes, scores, popularity rankings, and synopses. After cleaning, the dataset contained
over 16,000 manga entries with consolidated genre and theme categorizations.
2. User Interaction Data: A dataset of over 3.4 million user-manga interactions, capturing
ratings and engagement patterns. Missing values were carefully addressed to maintain
data integrity.
## Processes and Methodologies
1. Data Preprocessing:
○ Cleaning: Addressed missing values, standardized score formats, and merged
datasets on shared attributes.
○ Feature Engineering: Mapped detailed genres and themes to broader
categories for better analysis and model input.

2. Exploratory Data Analysis (EDA):
○ Distribution analysis of genres and themes.
○ Correlation studies to understand relationships between attributes like volumes,
chapters, and user scores.
3. Machine Learning Models:
○ K-Nearest Neighbors (KNN): Achieved 88% accuracy in predicting user
preferences.
○ Logistic Regression and Neural Networks: Further validated the robustness of
the recommendation logic, maintaining high accuracy levels (~90%).

4. Recommendation Techniques:
○ Cosine Similarity: Used for quick and straightforward recommendations based
on similarity scores.
○ Collaborative Filtering (TruncatedSVD): Decomposed user-manga interaction
matrices for deeper insight into latent preferences.

5. Evaluation Metrics:
○ Precision, recall, and F1-scores assessed the models' predictive performance.

○ Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) measured
the accuracy of continuous rating predictions.

Project Highlights
● Integration of both user interaction and metadata for a holistic recommendation strategy.
● A focus on scalability, ensuring the system's ability to handle large datasets efficiently.
● Use of an interactive web application (developed in Flask) to deliver real-time
recommendations to users.
Future Enhancements
● Hybrid Models: Combine content-based and collaborative filtering methods to further
refine recommendations.
● User Feedback Loop: Incorporate real-time feedback to adapt and improve
recommendations dynamically.
