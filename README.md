
# 🔥 Forest Fire Detection using K-Means Clustering

## 📌 Project Overview

This project focuses on identifying forest fire hotspots using **unsupervised machine learning (K-Means Clustering)**. Forest fires cause extensive damage to wildlife, property, and the environment. Timely detection of potential fire zones enables better resource allocation and disaster prevention strategies.

K-Means is applied to cluster areas based on features like temperature, humidity, wind speed, rainfall, and area burned. The model categorizes zones into different fire severity levels (e.g., low, medium, high).

---

## ❗ Problem Statement

Forest fires, also known as wildfires, pose a serious threat to ecosystems, wildlife, human life, and property. These fires are often triggered by dry weather conditions, high temperatures, and strong winds, making their detection and control highly challenging.

The goal of this project is to **detect and analyze fire-prone zones using machine learning techniques**, specifically **K-Means Clustering**, to identify patterns and group similar fire incidents based on climatological and environmental features. By doing so, we aim to:

- Proactively identify high-risk zones.
- Understand the conditions under which severe fires occur.
- Help authorities allocate resources efficiently for forest fire prevention and control.

This project provides valuable insights for forest management departments and environmental agencies by visualizing and clustering fire data to mitigate potential future disasters.

---

## 🎯 Objectives

- Identify and analyze **forest fire hotspots** using K-Means clustering.
- Use **climatological attributes** to detect fire-prone regions.
- Assist forest departments in making informed decisions for resource deployment.
- Provide **visual insights** and **cluster analysis**.

---

## 🧠 Machine Learning Technique

- **Algorithm:** K-Means Clustering
- **Type:** Unsupervised Learning

---

## 📁 Dataset

- **Source:** UCI Machine Learning Repository  
  - [Forest Fires Dataset](https://archive.ics.uci.edu/ml/datasets/forest+fires)
- **Features Used:**
  - Temperature (°C)
  - Relative Humidity (%)
  - Wind speed (km/h)
  - Rainfall (mm)
  - Area affected (ha)
  - Spatial coordinates (X, Y)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Output & Results

- 🔍 Forest areas were successfully clustered into **3 fire risk zones**:
  - Cluster 0: Low risk
  - Cluster 1: Medium risk
  - Cluster 2: High risk
- 📈 Elbow method used to determine the optimal number of clusters.
- 📌 Visualizations include:
  - Scatter plot of clusters by temperature and area
  - Seasonal trends and fire occurrences by month
  - Cluster-wise summary of climatological conditions

---

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Forest_Fire_Detection_using_K_Means_Clustering.ipynb
    ```
4. Run all cells to see preprocessing, clustering, visualizations, and predictions.

---

## 📌 Example Prediction

```python
new_fire = [[30, 18, 6.0, 0.0, 100]]
scaled_fire = scaler.transform(new_fire)
prediction = kmeans.predict(scaled_fire)
```

**Output:**
```
🔥 Predicted Risk Cluster: 2 (High)
```

---

## 🧠 Future Enhancements

- Add geospatial maps (GIS) for better hotspot visualization
- Integrate with weather APIs for real-time fire risk forecasting
- Build a web dashboard using Streamlit or Flask

---

## 📎 Author

- Name: Safrin M
- Role: Data Science Student Project Developer
- Tools: Python, Jupyter, scikit-learn, Seaborn, GitHub

---

## 🙌 Acknowledgements

- UCI Machine Learning Repository
- scikit-learn Documentation
- Matplotlib & Seaborn for visualizations
