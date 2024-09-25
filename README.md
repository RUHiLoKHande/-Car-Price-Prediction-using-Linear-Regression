Overview:
This project is a Machine Learning model that predicts the selling price of used cars based on various features such as the car’s name, year of manufacture, current price, kilometers driven, fuel type, transmission type, seller type, and the number of previous owners. The model utilizes Polynomial Regression to capture non-linear relationships between these features and the target variable, the car's selling price.

The dataset used in this project consists of various car attributes, and it is processed using PolynomialFeatures to generate polynomial combinations of the input features. The model is trained using LinearRegression and achieves a high R² score.

Tools and Libraries:

Programming Language: Python
Libraries Used:
pandas for data manipulation and analysis
numpy for numerical operations
matplotlib and seaborn for data visualization
scikit-learn for machine learning algorithms and data preprocessing
PolynomialFeatures for feature transformation
LinearRegression for model building
Features of the Project:

Data Preprocessing: Encoding categorical variables and normalizing the data.
Polynomial Feature Transformation: Capturing non-linear patterns in the data.
Model Training and Testing: Using Linear Regression with polynomial-transformed data.
Interactive User Input: Allowing the user to input custom car data to predict its selling price.
Model Performance: Displaying the R² score for model accuracy.
How to Run the Project:
Clone the repository from GitHub.
Install the necessary dependencies using pip install -r requirements.txt.
Run the car_price_prediction.py script.
Enter the details of the car for which you want to predict the selling price.
