# Movie_rate_prediction
Machine Learning, Python , Visualisation 
# 🎬 Movie Rating Prediction (IMDb India)

This project uses machine learning to predict IMDb-style movie ratings for Indian films based on various features such as genre, director, year, and vote count. It also includes feature engineering, model evaluation with regression metrics, and visualization using a confusion matrix heatmap.

---

## 📦 Dataset

The dataset used is: **IMDb Movies India.csv**  
It contains movie details such as:
- Name
- Genre
- Director
- Year
- Votes
- Rating

---

## ⚙️ Features of the Project

- Cleans and preprocesses the dataset
- Handles missing values and non-numeric vote entries
- Encodes categorical features (`Genre`, `Director`)
- Engineers new features:
  - **Director success rate** (average rating by director)
  - **Genre average rating**
- Trains a `RandomForestRegressor` model
- Evaluates performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Visualizes:
  - Feature importance
  - Confusion matrix of predicted vs actual (rounded) ratings

---

## 🧪 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab (for easy execution)

---

## 🚀 How to Run This Project (Google Colab Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the following files:
   - `movie_rate_prediction.py`
   - `IMDb Movies India.csv`
3. Open a new Colab notebook.
4. Run the following to upload and execute:

```python
# Upload files
from google.colab import files
uploaded = files.upload()

# Run your script
%run movie_rate_prediction.py


