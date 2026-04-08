🧬 Cancer Prediction using Logistic Regression

📌 Project Overview

Early detection of cancer can significantly improve treatment outcomes.
This project focuses on predicting whether a tumor is **benign** or **malignant** using machine learning techniques.

A classification model is built using Logistic Regression, which analyzes tumor features and predicts the diagnosis.

---

📂 Dataset

**Source:** YBI Foundation Cancer Dataset

The dataset includes:

* Tumor characteristics such as radius, texture, smoothness, etc.
* Target variable: `diagnosis`

  **M** → Malignant (Cancerous)
  **B** → Benign (Non-cancerous)

---

⚙️ Steps Performed

1. Import Libraries

* pandas
* matplotlib
* seaborn
* scikit-learn

2. Load Dataset

* Dataset is loaded directly from a GitHub URL using pandas

3. Exploratory Data Analysis (EDA)

* Displayed dataset head, info, and statistical summary
* Visualized distribution of `radius_mean` using histogram

4. Data Preprocessing

* Dropped unnecessary columns:

  * `id`
  * `Unnamed: 32`
* Defined:

  * Features (**X**)
  * Target (**y**)

5. Train-Test Split

* Split dataset into:

  * 70% training data
  * 30% testing data

6. Model Selection

* Used **Logistic Regression** with increased iterations:

  * `max_iter = 5000`

7. Model Training

* Trained the model using training data

8. Prediction

* Predicted outcomes on the test dataset

9. Evaluation

* Confusion Matrix (visualized using heatmap)
* Accuracy Score
* Classification Report (Precision, Recall, F1-score)

---

📊 Results

The model achieved strong classification performance.

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1-score

---

🛠️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

📈 Future Improvements

* Try advanced models (Random Forest, SVM, XGBoost)
* Perform hyperparameter tuning
* Apply feature scaling and feature selection
* Deploy the model using Flask or Streamlit

---

📁 Project Structure

```
├── Cancer_Prediction.ipynb
├── README.md
```

---

👨‍💻 Author

Ughade Kunal Ajaykumar

---

⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
