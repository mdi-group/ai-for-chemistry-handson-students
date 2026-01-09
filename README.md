# AI for Chemistry — Hands-On Sessions

Welcome to the **AI for Chemistry** hands-on sessions repository.  
This repo contains all interactive coding materials that accompany the taught part of the course. Each week, you will attend:

- **A taught session** introducing key concepts in machine learning for chemistry  
- **A hands-on session** where you will work through Jupyter notebooks to apply those concepts

All notebooks used in the hands-on sessions are stored in this repository and are designed to run on **Google Colab**.

---

## 📘 Course Overview

The course introduces modern AI and machine learning techniques used across computational and materials chemistry. The hands-on sessions cover the following topics:

1. **Exploratory Data Analysis (EDA)**  
   Understanding datasets, visualisation, feature inspection, and chemical intuition building.

2. **ML Descriptors for Chemistry**  
   Featurisation strategies including fingerprints, graph descriptors, and domain-specific representations.

3. **Basics of Machine Learning and classical ML**  
   Train/test splits, validation, metrics, overfitting, and workflows.
   Regression, classification, tree-based models, SVMs, and hyperparameter optimisation.

4. **Deep Learning**  
   Neural networks, training loops, regularisation, and chemical applications.

5. **Geometric Deep Learning**  
   Graph neural networks (GNNs), message passing, and structure-aware modelling for molecules and materials.

---

## 🚀 Getting Started

### 1. Requirements
To run the notebooks, you will need:

- A **Google account** (required for Google Colab)  
- A **Materials Project API key**  
  - Create an account at: https://legacy.materialsproject.org  
  - Generate an API key under *My Account → API Keys*

You will be prompted in certain notebooks to paste your API key when needed.

---

## ▶️ Running Notebooks in Google Colab

1. Go to **Google Colab**: https://colab.research.google.com  
2. In the “Open notebook” window, select the **GitHub** tab.  
3. In the search bar, type: mdi-group/ai-for-chemistry-handson

4. Select the notebook for the current week's session.  
5. Click **Open in Colab** if needed.

That’s it — you can now run the cells and start learning.

---

## 📁 Datasets

Some sessions require datasets.  
All datasets are available in the GitHub repo:

https://github.com/mdi-group/ai-for-chemistry-handson/tree/main/data


If a notebook requires data:

1. Download the dataset from the link above.  
2. In Colab, upload the file using:  
   **Left sidebar → Files → Upload**  

Alternatively, you can write code in a cell to fetch files directly from GitHub, but uploading is simplest.

---

## 💾 Saving Your Work on Colab

Colab does *not* automatically save notebooks back to GitHub, so you have several options:

### **Option 1: Save to Google Drive (recommended)**
- Go to **File → Save a copy in Drive**  
- This saves your personal editable version under *My Drive*  

### **Option 2: Download the notebook**
- **File → Download → Download .ipynb**  
- Useful for keeping a local archive

### **Option 3: Save a copy to GitHub**
- **File → Save a copy to GitHub**  
- You must authenticate your GitHub account  
- Note: You may prefer not to commit directly to the course repo

---

## 🛠 Structure of This Repository

```
ai-for-chemistry-handson/
│
├── week-*/ # Hands-on notebooks for each week
├── data/ # Datasets used in selected sessions
├── utils/ # Helper functions (if applicable)
└── README.md # Course overview (this file)
```


---

If you have any issues running the notebooks or accessing data, please raise an issue on the repository or ask during the practical session.

Happy coding, and welcome to **AI for Chemistry**!

