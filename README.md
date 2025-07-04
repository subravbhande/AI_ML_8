# 🧠 Task 8: K-Means Clustering – Mall Customer Segmentation

This project applies **unsupervised learning** using **K-Means clustering** to group mall customers into distinct segments based on annual income and spending behavior.

---

## 🎯 Objective

- Perform clustering using **K-Means**
- Visualize customer segments
- Use the **Elbow Method** to choose the optimal number of clusters
- Evaluate clustering using the **Silhouette Score**

---

## 📁 Dataset

**File:** `Mall_Customers.csv`  
Download: [Click here to download from Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

**Features Used for Clustering:**
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🧪 Steps Performed

1. Load and explore dataset
2. Select features for clustering
3. Apply the **Elbow Method** to find optimal K
4. Fit **KMeans** and assign cluster labels
5. Visualize clusters with **color-coding**
6. Evaluate with **Silhouette Score**

---

## 📊 Results

- **Optimal K:** 5 (found via Elbow Method)
- **Silhouette Score:** ~0.55 _(varies based on data and random state)_
- **Visualization:** Clear cluster boundaries in 2D scatter plot

---

## 💻 Tech Stack

- Python 3.13+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 How to Run

```bash
# 1. Clone this repository
git clone https://github.com/your-username/KMeans-Clustering-Mall-Customers.git

# 2. Install required packages
pip install -r requirements.txt

# 3. Run the script
python AI_ML_8.PY
