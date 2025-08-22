
### 🎶 Overview

This project explores **musical trend analysis and personalized recommendations** using machine learning techniques. By analyzing a dataset of over **600,000 Spotify tracks**, we build predictive models to estimate song popularity and provide insights into the features influencing it.

### 🔍 Key Features

* **Data Preprocessing & Cleaning**:

  * Handling missing values
  * Encoding non-numeric features
  * Standardization of numeric variables

* **Exploratory Data Analysis (EDA)**:

  * Correlation heatmaps
  * Feature-target relationship analysis
  * Descriptive statistics

* **Feature Engineering**:

  * Popularity weighted by genre
  * Energy/Danceability ratio
  * Duration normalization
  * Rolling averages

* **Modeling & Evaluation**:

  * **Linear Regression** (baseline & optimized with GridSearchCV)
  * **Random Forest Regressor** (with hyperparameter tuning)
  * Cross-validation for robust evaluation

* **Visualization**:

  * Predictions vs actual values
  * Residual distributions
  * Correlation matrices

### 📊 Results

* **Random Forest** outperformed Linear Regression with an R² of \~0.82 vs \~0.02 for regression.
* Feature engineering improved interpretability and predictive accuracy.
* Highlighted the limitations of simple linear models on complex, non-linear relationships in music data.

### ⚙️ Tech Stack

* **Python 3**
* **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/music-trends-analysis.git
   cd music-trends-analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Place your dataset (`dataset.csv`) in the project root.
4. Run the script:

   ```bash
   python main.py
   ```



Do you want me to also create a **ready-to-use `README.md` file** for your repo with markdown formatting, badges, and maybe sample plots placeholders?
