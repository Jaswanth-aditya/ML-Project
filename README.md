
# 📊 Student Performance Predictor

This project aims to predict students' math scores based on various numerical and categorical features such as reading and writing scores, gender, parental education level, and more.

## 🎯 Goal

To build and evaluate multiple machine learning regression models to predict the **math score** of a student, using a dataset from Kaggle: [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977).

## 🧠 Models Used

The following regression models were trained and evaluated. The one with the best performance is selected for final predictions:

- Random Forest Regressor
- Decision Tree Regressor
- Gradient Boosting Regressor
- Linear Regression
- XGBoost Regressor
- CatBoost Regressor
- AdaBoost Regressor

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for EDA & Visualization)
- Scikit-learn
- CatBoost, XGBoost
- Flask (for API)
- Custom Logging and Exception Handling
- Dill (for model serialization)

## 🗂️ Project Structure

```
src/
├── components/
│   ├── data_ingestion.py
│   ├── data_transformation.py
│   ├── model_trainer.py
├── pipeline/
│   ├── predict_pipeline.py
│   ├── train_pipeline.py
├── utils.py
├── logger.py
├── exception.py
```

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/Jaswanth-aditya/ML-Project.git
cd ML-Project
```

### Create and Activate a Virtual Environment

```bash
python -m venv venv
# Activate on Unix/macOS
source venv/bin/activate
# Activate on Windows
venv\Scripts\activate
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Then open `http://127.0.0.1:5000/` in your browser to test the Flask app.

## 📬 Contact

For any queries or suggestions, feel free to reach out or open an issue.

---


