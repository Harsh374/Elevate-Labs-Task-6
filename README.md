# 🌸 Elevate Labs - Task 6: K-Nearest Neighbors (KNN) Classification

This repository contains the implementation of the K-Nearest Neighbors (KNN) algorithm on the classic **Iris dataset**, as part of Task 6 for the Elevate Labs program.

## 🚀 Objective

To understand and apply the KNN classification algorithm, including:
- Instance-based learning
- Feature normalization
- Optimal `K` value selection
- Model evaluation using accuracy and confusion matrix
- Visualization of decision boundaries

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn (`sklearn`)
- Matplotlib
- Seaborn

---

## 📁 Dataset

We use the **Iris dataset**, which includes:
- 150 samples
- 3 species: *Setosa*, *Versicolor*, *Virginica*
- 4 features: Sepal Length, Sepal Width, Petal Length, Petal Width

---

## 🧪 Implementation Steps

1. **Load and Explore the Data**
2. **Preprocessing**
   - Drop irrelevant columns (e.g., ID)
   - Encode class labels
   - Normalize features
3. **Split Data** into training and testing sets
4. **Train KNN Classifier** using `KNeighborsClassifier`
5. **Evaluate** using:
   - Accuracy Score
   - Confusion Matrix
6. **Tune `K`**: Try multiple `K` values and visualize accuracy
7. **Visualize Decision Boundaries** using 2D projections of features

---

## 📊 Visualizations

- Accuracy vs. K value plot
- Confusion matrix
- Decision boundary plots for feature pairs

---

## ❓ Interview Prep: Key KNN Concepts

| Question | Insight |
|----------|---------|
| How does KNN work? | Based on majority voting of nearest neighbors |
| How to choose K? | Cross-validation, avoid over/underfitting |
| Why normalize? | Prevent features with larger scales from dominating |
| Time complexity? | O(n × d) per prediction |
| Pros & Cons? | Simple, but slow and sensitive to noise |
| Handles multi-class? | Yes, via majority voting |
| Distance metric? | Determines how "nearness" is calculated |

---

## 📂 File Structure

Elevate-Labs-Task-6/
├── Iris.csv # Dataset
├── knn_classification.ipynb # Main Jupyter notebook
├── README.md # Project documentation
└── visuals/ # (Optional) Saved plots


---

## 🧠 Learn More

- [Scikit-learn Docs](https://scikit-learn.org/stable/modules/neighbors.html)
- [Iris Dataset Info](https://en.wikipedia.org/wiki/Iris_flower_data_set)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change or improve.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Author**: [Harsh374](https://github.com/Harsh374)

