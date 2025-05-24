📊 House Rent Price Prediction
This project aims to build a machine learning model to predict residential rental prices based on property features such as location, number of bedrooms, parking spaces, usable area, and more.

The work is carried out in a Jupyter Notebook environment and includes exploratory data analysis, data preprocessing, feature selection, model training, and performance evaluation.

🏗️ Project Structure
Library Imports

Data Loading and Exploratory Analysis

Distribution of variables

Feature correlation

Visualizations using Seaborn and Matplotlib

Data Preprocessing

Handling missing values

Converting categorical variables

Removing outliers and infinite values

Modeling

Linear Regression

Random Forest Regressor

Evaluation using metrics like RMSE, R², and MAE

Model Validation

Performance comparison across models

📚 Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn

🛠️ How to Use
Clone the repository:

bash
Copiar
Editar
git clone https://github.com/yourusername/model-rent-house.git
cd model-rent-house
Install the dependencies:

bash
Copiar
Editar
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copiar
Editar
jupyter notebook model_rent_house.ipynb
📈 Results
The best-performing model showed strong predictive capabilities for rental prices based on the available features. Metrics such as RMSE and R² indicate good generalization and low prediction error, particularly with the Random Forest algorithm.

📌 Notes
The dataset was cleaned to remove missing and infinite values to avoid issues during visualization and modeling.

This project provides a solid foundation for further enhancements, such as hyperparameter tuning and experimenting with advanced models (e.g., XGBoost, LightGBM).

