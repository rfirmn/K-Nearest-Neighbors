# Drug Classification using K-Nearest Neighbors (KNN)

This project is a machine learning implementation using the **K-Nearest Neighbors (KNN)** algorithm to classify which drug should be prescribed to a patient based on their medical attributes.

## 📊 Dataset

The dataset used contains medical information of 200 patients with the following features:

- `Age`: Age of the patient
- `Sex`: Gender (`Male` / `Female`)
- `BP`: Blood Pressure level (`HIGH`, `NORMAL`, `LOW`)
- `Cholesterol`: Cholesterol level (`HIGH`, `NORMAL`)
- `Na_to_K`: Sodium to Potassium ratio in blood

### 🎯 Target

- `Drug`: The type of drug prescribed (`DrugA`, `DrugB`, `DrugC`, `DrugX`, `DrugY`)

## 🧠 Machine Learning Model

The K-Nearest Neighbors (KNN) algorithm is used for classification.

### Steps:
1. **Data Preprocessing**
   - Convert categorical features to numerical using one-hot encoding or label encoding
   - Split the dataset into training and testing sets
2. **Model Training**
   - Use `KNeighborsClassifier` from `sklearn.neighbors`
3. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

## 🧪 Evaluation Results

Includes metrics such as:
- Precision, Recall, F1-Score per class
- Overall Accuracy
- Confusion matrix visualization

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the dependencies using:

```bash
pip install -r requirements.txt
````

## 📂 Files

* `drug200.csv`: Dataset used for the project
* `drug_classification_knn.ipynb`: Main notebook with code and visualizations

## 📌 Usage

Clone the repository and run the notebook:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
jupyter notebook drug_classification_knn.ipynb
```

---
