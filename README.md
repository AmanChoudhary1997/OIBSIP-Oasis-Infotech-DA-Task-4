![Screenshot 2024-10-30 094336](https://github.com/user-attachments/assets/510189c0-a063-4d2e-8374-d5eddc976372)

# Google Play Store Apps Analysis

## Project Overview
This project aims to analyze and derive insights from Google Play Store apps data. Through data cleaning, exploratory data analysis (EDA), and a simple machine learning model, we uncover patterns in app characteristics, ratings, categories, pricing, and user sentiments. Additionally, we predict app prices based on several features, using regression analysis to interpret potential influences on pricing.

## Technology Used
- Python
- Pandas, NumPy: Data manipulation and cleaning
- Matplotlib, Seaborn: Data visualization
- Scikit-Learn: Machine learning (Linear Regression, data preprocessing)
- Jupyter Notebook: Code and analysis environment

## Dataset
The analysis uses two datasets:
1. **apps.csv**: Contains app information such as app name, category, rating, reviews, installs, size, price, and more.
2. **user_reviews.csv**: Contains user reviews for apps, including sentiment labels.


## Key Steps
1. **Data Preparation and Cleaning**:
   - Dropped duplicate entries and handled missing values.
   - Cleaned `Installs` and `Price` columns to convert them into usable numerical formats.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed app distribution across categories.
   - Visualized the distribution of ratings and pricing across categories.
   - Conducted sentiment analysis on user reviews to gauge customer perception.
   
3. **Machine Learning Model**:
   - Built a regression model to predict app prices based on features such as app category, rating, and number of installs.
   - Evaluated model performance using Mean Squared Error (MSE) and R² score.

## Key Insights
- **App Distribution**: Most apps belong to popular categories such as "Games," "Education," and "Productivity."
- **Rating Distribution**: App ratings generally range between 4.0 and 4.5, indicating user satisfaction.
- **App Size vs. Price**: Larger apps tend to be priced higher, though many free apps dominate across categories.
- **Sentiment Analysis**: User reviews are predominantly positive, suggesting good app quality.
- **Price Prediction Model**: The model showed a low R² score, indicating limited effectiveness in predicting app prices, possibly due to the lack of price variance or other influential factors not captured in the dataset.

## Recommendations
- **App Quality**: Maintain high-quality user experiences, as high ratings and positive reviews strongly influence app popularity.
- **Pricing Strategy**: Optimize app size and pricing to attract more downloads, with consideration for the category's typical user base.
- **Enhanced Model Features**: Consider incorporating additional features (e.g., app update frequency, developer reputation) to improve the predictive power of pricing models.

This analysis provides a foundation for data-driven strategies to enhance app offerings, targeting customer preferences and improving engagement on the Google Play Store.
