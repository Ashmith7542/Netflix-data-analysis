## Project Description – Netflix Data Analysis

This project explores the **Netflix Movies & TV Shows dataset** to uncover insights about content availability, genre distribution, and release trends over time. Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, the analysis focuses on understanding how Netflix’s content library has evolved and what types of shows dominate the platform.

In addition to Exploratory Data Analysis (EDA), the project also includes a Machine Learning Prediction Model that predicts whether a content item is a Movie or a TV Show based on multiple features such as release year, duration, and country.

### Key Objectives

* Analyze the proportion of **Movies vs TV Shows** on Netflix.
* Identify the **most popular genres** and categories.
* Explore **release year trends** to see how Netflix’s content library has grown.
* Visualize distributions across **ratings, durations, and countries**
* Build a prediction model to classify content type (Movie or TV Show).
* Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrix.
* Analyze feature importance to identify which attributes influence predictions the most.
 
### Tools & Technologies

* **Python**: Data cleaning and manipulation.
* **Pandas / NumPy**: Data wrangling and preprocessing.
* **Matplotlib / Seaborn**: Data visualization.
* **Jupyter Notebook**: Interactive exploration and reporting.
* Scikit-learn: Machine Learning (Random Forest Classifier).

### Outcomes & Insights

* Netflix has a significantly higher proportion of **Movies compared to TV Shows**.
* The **Documentaries, Dramas, and Stand-Up Comedy** categories are among the most represented genres.
* A surge in content releases is observed post-2015, peaking around 2018.
* Content availability is highly skewed toward a few key countries.
* The Machine Learning Prediction Model (Random Forest Classifier) achieved perfect performance with:
  * Accuracy: 100%
  * Precision: 100%
  * Recall: 100%
  * F1-score: 100%
* The model was able to correctly classify every instance of Movie vs TV Show in the dataset.
* Feature importance analysis revealed that duration, release year, and listed genres play the most significant role in classification.

### How to Use

1. Download the dataset from [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows).
2. Place the CSV file in the `data/` folder.
3. Install dependencies:

   ```bash/terminal
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebooks:

   * Netflix_Analysis.ipynb → Exploratory Data Analysis
   * Netflix_Prediction.ipynb → Machine Learning Model

   ```bash/terminal
   jupyter notebook
   ```
