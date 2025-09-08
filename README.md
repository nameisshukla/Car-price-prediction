# Car-price-prediction
A machine learning + Flask web app that predicts the selling price of used cars based on features like year, present price, kms driven, fuel type, transmission, and seller type.

📊 Dataset

The dataset includes:

Year – Year of manufacture

Present Price – Current ex-showroom price

Kms Driven – Kilometers driven by the car

Fuel Type – Petrol/Diesel

Transmission – Manual/Automatic

Seller Type – Dealer/Individual

Owner – Number of previous owners

(Dataset source: Kaggle Used Car Dataset
)

🛠 Tech Stack

Python 3

Flask (Web framework)

Pickle (Model serialization)

Scikit-learn (ML model training)

NumPy, Pandas (Data preprocessing)

HTML/CSS (Frontend for user input form)

🔍 Workflow

Data Preprocessing – handled missing values, log-transformed kms driven, encoded categorical features.

Model Training – tested multiple regression models, finalized Random Forest Regressor for best performance.

Model Serialization – saved trained model as random_forest_regression_model.pkl.

Flask App Integration – built a UI form to take inputs & display predicted car price.

📈 Results

Random Forest Regressor gave the best accuracy among tested models.

Key influential features: Year, Present Price, Fuel Type.

🚀 How to Run Locally

Clone the repository:

git clone https://github.com/yourusername/Car_price_prediction.git
cd Car_price_prediction


Install dependencies:

pip install -r requirements.txt


Run the Flask app:

python app.py


Open in browser:

http://127.0.0.1:5000/

💡 Future Improvements

Deploy on Heroku/Render for live demo.

Add Streamlit UI for modern interface.

Experiment with XGBoost/CatBoost for better accuracy.
