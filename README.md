# Rossmann Sales Prediction Project

## Project Story

### The Challenge
Building a machine learning model to predict daily sales for Rossmann stores with target accuracy of 85% or higher.

### The Journey

#### Phase 1: Data Exploration
- Started with Rossmann Store Sales dataset containing over 1 million records
- Data included store information, promotions, holidays, and competition details
- Initial analysis showed missing values in competition and promo2 columns

#### Phase 2: Data Preprocessing  
- Handled missing values by filling with zeros and medians
- Merged store details with sales data
- Created new features from date (year, month, week)
- Encoded categorical variables for machine learning

#### Phase 3: Model Training
We tested multiple algorithms:
- Linear Regression: 37% accuracy ❌
- Decision Tree: 82% accuracy ✅
- Gradient Boosting: 63% accuracy ❌
- Random Forest: 90% accuracy ✅

Random Forest emerged as the clear winner!

#### Phase 4: Performance Optimization
- Initial training with 100,000 samples: 90.41% accuracy
- Full dataset training: 94.02% accuracy 🎯
- Final Mean Absolute Error: €539.70

#### Phase 5: Web Application
Built a Streamlit web app with:
- User-friendly input forms
- Real-time predictions
- Clear business explanations
- Professional interface

### The Solution
Our final model takes 12 key features:
- Store details (ID, type, size, assortment)
- Time features (day of week, month, year, week)
- Business factors (promotions, holidays)
- Competition information (distance to nearest competitor)

### Live Demo
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](your-live-demo-link)

### Technical Stack
- Python, Scikit-learn, Pandas
- Random Forest Algorithm
- Streamlit for web interface
- Joblib for model serialization

