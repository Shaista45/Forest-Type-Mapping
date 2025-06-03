# 🌲 Forest Type Mapping using AI

## 📚 Project Overview
This AI-based project is focused on **mapping forest cover types** using supervised and unsupervised machine learning algorithms. It uses the UCI Forest CoverType dataset and runs entirely on **Google Colab**, making it easy to access and execute.

The project aims to accurately classify forest types and analyze patterns using techniques like:
- **Classification:** K-Nearest Neighbors (KNN), Naive Bayes, Random Forest, Decision Tree
- **Clustering:** K-Means
- **Visualization:** PCA for 2D projection, confusion matrix, and performance metrics

## 💡 Key Objectives
- Predict forest type based on cartographic variables
- Evaluate model performance using Accuracy, Precision, Recall, and F1-Score
- Visualize clustering and classification results
- Compare and improve algorithm performance

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository - Forest CoverType](https://archive.ics.uci.edu/ml/datasets/covertype)
- **Classes:** 7 forest cover types
- **Instances:** 581,012
- **Features:** 54 (10 quantitative + 44 binary wilderness/soil type features)

## 🛠️ Technologies Used
- **Platform:** Google Colab (Python 3.x)
- **Libraries:** `scikit-learn`, `pandas`, `matplotlib`, `seaborn`, `numpy`, `plotly`

## 🚀 How to Use
1. Open the Colab notebook: [Click Here to Run](https://colab.research.google.com/)
2. Upload the dataset or use the link to download from UCI
3. Follow the step-by-step execution in the notebook

## 📈 Model Evaluation
- Performance comparison between classifiers
- F1 Score, Accuracy, Precision, and Recall
- Visualization of results and clusters

## 🧠 Future Enhancements
- Add deep learning-based classifiers (e.g., DNN, CNN)
- Introduce auto-ML for hyperparameter tuning
- Real-time web deployment using Streamlit or Flask


