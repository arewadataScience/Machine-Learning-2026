<div align="center">

# 🤖 Introduction to Machine Learning
### A Summer School Course

**Based on:** *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* — Aurélien Géron  
**Instructors:** nsin–Stevens Point

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

</div>

---

## Table of Contents

- [About This Course](#about-this-course)
- [Key Features](#key-features)
- [Prerequisites](#prerequisites)
- [Course Structure](#course-structure)
- [Weekly Schedule](#weekly-schedule)
- [Lab Notebooks](#lab-notebooks)
- [Getting Started](#getting-started)
- [Recommended Resources](#recommended-resources)
- [Instructor](#instructor)

---

## About This Course

This is a 12-week intensive summer school on Machine Learning, designed for students with some Python experience. Each session is 2 hours: **1 hour of lecture** followed by **1 hour of hands-on lab** in Google Colab.

The course takes a practical, code-first approach — every concept is immediately reinforced with working scikit-learn code. By the end, students can build, evaluate, and reason about a wide range of ML models.

---

## Key Features

- 📚 **12 lecture decks** — covers the full supervised + unsupervised ML landscape
- 💻 **12 Colab-ready lab notebooks** — Guided → Fill-in-the-blank → Challenge structure
- 🔬 **Real datasets** — MNIST, California Housing, Iris, Breast Cancer, and more
- 🧪 **Consistent pedagogy** — every lab has the same 3-part format for predictable pacing
- 📖 **Textbook-aligned** — all slides reference Géron's *Hands-On ML* (3rd ed.)

---

## Prerequisites

| Skill | Level Required |
|---|---|
| Python | Some experience (loops, functions, lists) |
| Math | Basic algebra; no calculus required |
| Statistics | Mean, variance, correlation |
| Machine Learning | None — this is the starting point |

Students should be comfortable reading Python code. No prior ML or deep learning experience is assumed.

---

## Course Structure

```
summer-school-ml/
├── slides/
│   ├── Week_1_Week_2_Ch1.pptx          # Intro to ML
│   ├── Week_3_Week_4_Ch2.pptx          # End-to-End ML Project
│   ├── week_5-1_Classification.pptx
│   ├── week_6-1_Classification_2.pptx
│   ├── Week_7_Training_Models.pptx
│   ├── week_10_1_SVM_Week10_Part1.pptx
│   ├── week_10_2_SVM_Week10_Part2.pptx
│   ├── Week_11_DecisionTrees.pptx
│   ├── Week_12_EnsembleLearning.pptx
│   ├── Week_13_NeuralNetworks.pptx
│   ├── Week_14_Ch7.pptx                # Dimensionality Reduction (bonus)
│   └── Week_14_UnsupervisedLearning.pptx
├── labs/
│   ├── Lab_01_Python_Pandas_Warmup.ipynb
│   ├── Lab_02_California_Housing_EDA.ipynb
│   ├── Lab_03_Preprocessing_Pipelines.ipynb
│   ├── Lab_04_Binary_Classification_MNIST.ipynb
│   ├── Lab_05_Multiclass_Error_Analysis.ipynb
│   ├── Lab_06_Training_Models_GradientDescent.ipynb
│   ├── Lab_07_Regularization_LogisticRegression.ipynb
│   ├── Lab_08_SVM.ipynb
│   ├── Lab_09_DecisionTrees.ipynb
│   ├── Lab_10_EnsembleLearning.ipynb
│   ├── Lab_11_NeuralNetworks.ipynb
│   └── Lab_12_UnsupervisedLearning.ipynb
└── README.md
```

---

## Weekly Schedule

**Format:** 2 hours/week · 1hr lecture + 1hr lab · 12 weeks

| Week | Topic | Slides | Lab | Key Concepts |
|:---:|---|:---:|:---:|---|
| 1 | Introduction to ML | [📊 Slides](slides/Week_1_Week_2_Ch1.pptx) | [💻 Lab 01](labs/Lab_01_Python_Pandas_Warmup.ipynb) | ML types, the ML landscape, Python/NumPy/Pandas |
| 2 | End-to-End ML Project — EDA | [📊 Slides](slides/Week_3_Week_4_Ch2.pptx) | [💻 Lab 02](labs/Lab_02_California_Housing_EDA.ipynb) | Problem framing, data exploration, geographic visualization |
| 3 | Data Preprocessing & Pipelines | [📊 Slides](slides/Week_3_Week_4_Ch2.pptx) | [💻 Lab 03](labs/Lab_03_Preprocessing_Pipelines.ipynb) | Imputation, scaling, `Pipeline`, `ColumnTransformer` |
| 4 | Binary Classification | [📊 Slides](slides/week_5-1_Classification.pptx) | [💻 Lab 04](labs/Lab_04_Binary_Classification_MNIST.ipynb) | SGD classifier, precision, recall, F1, ROC/AUC |
| 5 | Multiclass Classification & Error Analysis | [📊 Slides](slides/week_6-1_Classification_2.pptx) | [💻 Lab 05](labs/Lab_05_Multiclass_Error_Analysis.ipynb) | OvR, OvO, confusion matrix heatmap, error profiling |
| 6 | Training Models — Linear Regression & GD | [📊 Slides](slides/Week_7_Training_Models.pptx) | [💻 Lab 06](labs/Lab_06_Training_Models_GradientDescent.ipynb) | Normal equation, batch/SGD/mini-batch gradient descent |
| 7 | Regularization & Logistic Regression | *(see note below)* | [💻 Lab 07](labs/Lab_07_Regularization_LogisticRegression.ipynb) | Ridge, Lasso, Elastic Net, logistic regression, decision boundary |
| 8 | Support Vector Machines | [📊 Slides](slides/week_10_1_SVM_Week10_Part1.pptx) · [Part 2](slides/week_10_2_SVM_Week10_Part2.pptx) | [💻 Lab 08](labs/Lab_08_SVM.ipynb) | Max margin, kernel trick, RBF/polynomial kernels, SVR |
| 9 | Decision Trees | [📊 Slides](slides/Week_11_DecisionTrees.pptx) | [💻 Lab 09](labs/Lab_09_DecisionTrees.ipynb) | CART, Gini impurity, depth regularization, feature importance |
| 10 | Ensemble Learning & Random Forests | [📊 Slides](slides/Week_12_EnsembleLearning.pptx) | [💻 Lab 10](labs/Lab_10_EnsembleLearning.ipynb) | Bagging, voting, AdaBoost, Gradient Boosting, Random Forests |
| 11 | Neural Networks | [📊 Slides](slides/Week_13_NeuralNetworks.pptx) | [💻 Lab 11](labs/Lab_11_NeuralNetworks.ipynb) | Perceptron, Keras Sequential API, Dropout, BatchNorm |
| 12 | Unsupervised Learning | [📊 Slides](slides/Week_14_UnsupervisedLearning.pptx) | [💻 Lab 12](labs/Lab_12_UnsupervisedLearning.ipynb) | k-Means, elbow method, silhouette score, DBSCAN, GMMs |

> **⚠️ Note on Week 7:** Slides for regularization and logistic regression are not yet in this repository. The lab notebook is complete and self-contained. Suggested reading: Géron Ch. 4, sections on Ridge, Lasso, and Logistic Regression.

---

## Lab Notebooks

Every lab follows the same structure to make pacing predictable:

| Section | Duration | Description |
|---|:---:|---|
| **Part A — Guided** | ~20 min | Pre-filled code — run cells and observe outputs carefully |
| **Part B — Fill in the Blank** | ~25 min | Skeleton code with `???` placeholders to complete |
| **Part C — Challenge** | ~15 min | Open-ended extension problems for fast finishers |

All notebooks are designed for **Google Colab** — no local setup required. Click any badge below to open directly:

| Lab | Topic | Open in Colab |
|:---:|---|:---:|
| 01 | Python, NumPy & Pandas Warmup | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_01_Python_Pandas_Warmup.ipynb) |
| 02 | California Housing EDA | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_02_California_Housing_EDA.ipynb) |
| 03 | Preprocessing & Pipelines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_03_Preprocessing_Pipelines.ipynb) |
| 04 | Binary Classification on MNIST | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_04_Binary_Classification_MNIST.ipynb) |
| 05 | Multiclass Classification & Error Analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_05_Multiclass_Error_Analysis.ipynb) |
| 06 | Training Models & Gradient Descent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_06_Training_Models_GradientDescent.ipynb) |
| 07 | Regularization & Logistic Regression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_07_Regularization_LogisticRegression.ipynb) |
| 08 | Support Vector Machines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_08_SVM.ipynb) |
| 09 | Decision Trees | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_09_DecisionTrees.ipynb) |
| 10 | Ensemble Learning & Random Forests | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_10_EnsembleLearning.ipynb) |
| 11 | Neural Networks with Keras | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_11_NeuralNetworks.ipynb) |
| 12 | Unsupervised Learning — Clustering | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/labs/Lab_12_UnsupervisedLearning.ipynb) |

> **Replace `YOUR_USERNAME/YOUR_REPO`** in the Colab badge URLs above with your actual GitHub username and repository name.

---

## Getting Started

### Option 1: Google Colab (Recommended)

No setup needed. Click any "Open in Colab" badge above. All required packages (scikit-learn, TensorFlow/Keras, matplotlib, pandas) are pre-installed in Colab.

> 💡 For Lab 11 (Neural Networks), go to **Runtime → Change runtime type → T4 GPU** for faster training.

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# Create a virtual environment
python -m venv ml-env
source ml-env/bin/activate       # macOS/Linux
ml-env\Scripts\activate          # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook labs/
```

**`requirements.txt`:**
```
numpy>=1.24
pandas>=2.0
matplotlib>=3.7
scikit-learn>=1.3
tensorflow>=2.13
jupyter
```

---

## Recommended Resources

### Primary Textbook
- 📘 [**Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow** (3rd ed.) — Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
  All slides in this course are based on this book.

### Supplementary Reading
- 📗 [Python for Data Analysis — Wes McKinney](https://wesmckinney.com/book/) *(free online)*
- 📙 [Python Data Science Handbook — Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/) *(free online)*

### Video Series
- 🎥 [YouTube series on Hands-On ML book chapters](https://www.youtube.com/playlist?list=PLr3-oFRsHRaZwmVUPMvnDUZV-j2zaK5zU)

### Practice & Competitions
- 🏆 [Kaggle](https://www.kaggle.com/) — competitions and free courses
- 💡 [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)

---

## Instructor

**Ibrahim Said Ahmad, PhD**  
Assistant Professor, Department of Computing and New Media Technologies  
University of Wisconsin–Stevens Point

| | |
|---|---|
| 🔬 Research | NLP, Computational Social Science, Low-Resource Languages |
| 🏆 Awards | Best Paper ACII 2025 · Best Resource Paper ACL 2025 · SemEval Best Task Award ACL 2025 |
| 💰 Grants | $400k+ from Google Research, Lacuna Fund, Oracle |
| 🌍 Initiatives | Co-founder [HausaNLP](https://github.com/hausaNLP) · Co-founder [ArewaDataScience](https://arewadatascience.github.io) |

---

## Contributing

Found a bug in a notebook? Have a suggestion for a challenge problem? Pull requests are welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b fix/lab-03-typo`)
3. Commit your changes
4. Open a pull request

---

## License

This course material is released under the [MIT License](LICENSE). The slides are based on content from *Hands-On Machine Learning* by Aurélien Géron (O'Reilly Media) — please respect the original work's copyright when sharing.

---

<div align="center">

Made with ❤️ for students learning ML · Summer 2025

</div>
