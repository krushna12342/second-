# Crop Yield Prediction System using Machine Learning 🌾

![Streamlit Application]()

This project is a complete **Machine Learning System** built in Python that predicts crop yield based on agricultural and environmental factors. It helps farmers, agricultural planners, and researchers make data-driven decisions that can improve productivity and resource management.

## 🚀 Features
- **Data Preprocessing & EDA**: Synthesizes structured data, handles categorical features using OneHot Encoding, numerical features with Standard Scaling, and generates extensive visualization graphics.
- **Machine Learning Models**: Implements and evaluates Linear Regression, Decision Trees, and Random Forests using `.scikit-learn`.
- **Performance Evaluation**: Provides detailed comparisons using R² Score, MSE, and MAE to select the best-performing algorithm.
- **Interactive Web Interface**: A beautifully designed, user-friendly Streamlit application that allows real-time predictions based on input data.

## 📁 Project Structure

```bash
crop_yield_prediction/
├── app/
│   ├── app.py                      # Main Streamlit web application
│   └── assets/                     # Graphical assets like correlation matrices
├── model/
│   ├── train.py                    # Training pipeline & evaluation script
│   ├── best_model.pkl              # Pickled best ML pipeline
│   └── evaluation_results.csv      # Metrics output for comparisons
├── dataset/
│   └── crop_yield_data.csv         # The generated synthetic dataset
├── dataset_generator.py            # Script used to generate dummy dataset
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
```

## 🛠️ Technologies Used
- **Language**: Python 3.x
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Data Visualization**: Matplotlib, Seaborn
- **Web Interface**: Streamlit

## 💻 How to Run This Project

1. **Clone the repository** (or download the source code).
2. **Navigate into the project directory**:
   ```sh
   cd crop_yield_prediction
   ```
3. **Install the dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
4. **Generate the dataset** (if no dataset is provided):
   ```sh
   python dataset_generator.py
   ```
5. **Train the models**:
   ```sh
   python model/train.py
   ```
   *(This will train the regression algorithms, save evaluations, and store `best_model.pkl` in the `model` folder)*
6. **Launch the Web Interface**:
   ```sh
   streamlit run app/app.py
   ```
   *(A new tab will open in your default browser)*

## 🎓 Resume-Ready Description for Your Portfolio
> **Developed a full-stack Machine Learning web application to predict crop yields with highly accurate regression models (e.g., Random Forest). Formulated an end-to-end data pipeline including generating 2,000+ synthetic data points, comprehensive feature engineering, scaling, and EDA using Pandas and Seaborn. Evaluated models based on R² and MSE scores, deploying the most performant model via a responsive Streamlit UI to assist farmers and agricultural analysts in data-driven crop planning.**

---
*Created as part of a beginner's portfolio project in Machine Learning & Python.*
