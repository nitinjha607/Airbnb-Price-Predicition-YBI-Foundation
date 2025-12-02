🏠 Airbnb Price Prediction
📋 Project Overview
Machine Learning system to predict Airbnb rental prices using property features, amenities, and location data. Built during Data Science internship at YBI Foundation.

🚀 Quick Start
Run in Google Colab
https://colab.research.google.com/assets/colab-badge.svg

Local Installation
bash
git clone https://github.com/YOUR_USERNAME/airbnb-price-prediction.git
cd airbnb-price-prediction
pip install -r requirements.txt
jupyter notebook airbnb_price_prediction.ipynb
🛠️ Technologies Used
Python: Pandas, NumPy, Scikit-learn, XGBoost

Visualization: Matplotlib, Seaborn

Web Framework: Flask

Tools: Google Colab, Git, GitHub

📊 Model Performance
Algorithm Comparison
Model	R² Score	MAE ($)	Training Time
XGBoost	0.87	23.45	127s
Random Forest	0.84	26.18	90s
Decision Tree	0.78	31.24	13s
Linear Regression	0.65	42.35	3s
Top Features
Location Score (23.4%)

Bedroom Count (18.7%)

Amenity Score (15.6%)

Host Experience (8.9%)

🔧 Key Features
Data Pipeline: Cleaning, preprocessing, feature engineering

Multiple Algorithms: Linear Regression, Decision Trees, Random Forest, XGBoost

Web Deployment: Flask application with API

Business Insights: Pricing factors and recommendations

💼 Business Impact
15-25% potential revenue optimization for hosts

87% prediction accuracy (R² Score)

$23.45 average prediction error (MAE)

🎯 Usage Examples
Make Predictions
python
from models.predictor import PricePredictor

predictor = PricePredictor.load_model('models/xgboost_model.pkl')
price = predictor.predict({
    'bedrooms': 2,
    'bathrooms': 1,
    'accommodates': 4,
    'neighborhood': 'Manhattan'
})
Run Web App
bash
cd app
pip install -r requirements.txt
python app.py
# Open: http://localhost:5000
📈 Results Visualization
Price distribution analysis

Feature importance charts

Model comparison plots

Prediction accuracy visualizations

🤝 Contributing
Fork the repository

Create feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open Pull Request

📄 License
Distributed under MIT License. See LICENSE for more information.

👨‍💻 Author
Nitin Jha - Data Science Intern at YBI Foundation

GitHub: @YOUR_USERNAME

Email: nitingjha075@gmail.com

🙏 Acknowledgments
Dr. Alok Yadav (Mentor, YBI Foundation)

YBI Foundation Team

ABES Engineering College
