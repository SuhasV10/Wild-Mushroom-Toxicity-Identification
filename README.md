# Wild Mushroom Toxicity Identification & Poison Prevention

An automated machine learning pipeline to classify wild mushrooms as **edible** or **poisonous** using macroscopic morphological characteristics from the UCI Mushroom Dataset[cite: 2, 6].

## 🚀 Run in Google Colab
The complete end-to-end pipeline, data auditing, and visualizations are tested and executed in Google Colab[cite: 2, 6]:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gddG0rBzkUWIu-TN8mUV7290j8dZpaqB?usp=sharing)

## 📌 Project Overview
* **Application Domain:** Mycology & Food Safety Toxicology[cite: 2, 6]
* **Target Algorithms:** CART Decision Tree (Gini Impurity), Cost-Complexity Pruning (`ccp_alpha`), Cost-Sensitive Learning, and Bernoulli Naive Bayes[cite: 2, 6].
* **Dataset:** Audubon Society / UCI Mushroom Dataset (8,124 specimens, 22 categorical attributes, 117 one-hot encoded binary features)[cite: 2, 6].

## 📊 Key Highlights & Results
* **Zero False Negatives:** Achieved via cost-sensitive learning ($w = 50$) to ensure zero poisonous mushrooms are misclassified as edible, preventing lethal toxicological errors[cite: 2, 6].
* **Model Performance:** The unpruned and cost-sensitive trees achieve 100% test accuracy on the held-out split, outperforming the Bernoulli Naive Bayes baseline[cite: 2, 6].
* **Feature Importance:** Confirmed that *Odor* acts as the primary dominant discriminator across decision models[cite: 2, 6].

## 📁 Repository Contents
* `Problem44_Mushroom_Toxicity.ipynb`: The primary executable Google Colab Jupyter notebook[cite: 2, 6].
* `Problem44_Final_Report.pdf`: The formal technical project report document[cite: 2, 6].
