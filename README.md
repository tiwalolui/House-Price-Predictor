🏠 House Price Prediction using Linear Regression

This project predicts California house prices using two approaches:

- Scikit-learn Linear Regression
- Linear Regression from scratch using Gradient Descent

The goal was not just to make predictions, but to understand how linear regression works under the hood and compare both methods.



 # Project Highlights

- Explored the California Housing dataset
- Checked for missing values and duplicates
- Analyzed feature correlations
- Visualized trends using scatter plots
- Built and evaluated a Scikit-learn regression model
- Implemented Gradient Descent manually
- Improved manual model performance using feature scaling
- Compared both approaches



# Dataset

This project uses the built-in California Housing Dataset from Scikit-learn.

Features:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target:

- Median House Price



# Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn



# Project Structure

house-price-prediction/
│
├── sklearn_model.py
├── gradient_descent.py
├── README.md
└── requirements.txt



  # Model Performance

Scikit-learn Linear Regression

- MAE: ~0.53
- MSE: ~0.56
- R² Score: ~0.58

Gradient Descent (From Scratch)

- Before Scaling
  
  - MAE: ~0.81
  - R²: ~0.21

- After Scaling
  
  - MAE: ~0.56
  - MSE: ~0.59
  - R² Score: ~0.55

Key Insight

Applying feature scaling significantly improved the gradient descent model and brought its performance close to Scikit-learn’s implementation.



# Visual Insights

- Median income showed a strong positive relationship with house price.
- A price cap in the dataset created a ceiling effect around higher house values.
- Scatter plots helped reveal overall trends and data limitations.

---

▶️ How to Run

1. Clone the repository

git clone https://github.com/username/house-price-prediction.git
cd house-price-prediction

2. Install dependencies

pip install -r requirements.txt

3. Run Scikit-learn model

python sklearn_model.py

4. Run Gradient Descent model

python gradient_descent.py



# What I Learned

- How to prepare and explore real-world datasets
- The importance of feature scaling in optimization
- How gradient descent updates weights and bias
- How to evaluate regression models using:
  - MAE
  - MSE
  - R² Score
- How to compare a custom ML implementation with a library model

---

# Future Improvements

- Build a Streamlit web app for user predictions
- Save trained model with pickle for deployment
- Add interactive maps for location-based analysis
- Experiment with other regression algorithms

---

# Author

[IGE TIWALOLU]
