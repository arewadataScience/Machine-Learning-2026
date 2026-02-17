# ArewaDS — Programming for AI & Machine Learning

> **Free, open-access online course. Part of the [ArewaDataScience](https://arewadatascience.github.io) initiative.**  
> Every session is on **Zoom** — open to everyone, no applications needed.  
> Slides and video recordings are shared after each session.

---

## 📋 Table of Contents

- [About the Course](#about-the-course)
- [How It Works](#how-it-works)
- [Tools & Setup](#tools--setup)
- [Learning Outcomes](#learning-outcomes)
- [Weekly Schedule](#weekly-schedule)
- [Resources](#resources)
- [Community & Contact](#community--contact)

---

## About the Course

This course introduces the principles and practical skills needed to implement and evaluate fundamental machine learning algorithms in Python. Following **Aurélien Géron's *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* (3rd Edition)** (Chapters 1–9), you will gain hands-on experience building models, processing data, and understanding the computational reasoning behind AI systems.

The course is offered **completely free** as part of the **ArewaDataScience Fellowship** initiative, open to anyone who wants to join — no formal enrollment required.

| Detail | Info |
|--------|------|
| 📅 Format | Live Zoom sessions |
| 💰 Cost | Free |
| 📚 Primary Text | Géron, *Hands-On ML with Scikit-Learn & TensorFlow*, 3rd Ed. |
| 🔗 Materials | Slides & recordings added after every session |
| 🌍 Open to | Everyone |

---

## How It Works

1. **Join the Zoom link** shared via our community channels before each session.
2. **Follow along** with the slides (uploaded here after each class).
3. **Watch the recording** if you missed a live session — all recordings are linked in the schedule below.
4. **Complete the labs and assignments** at your own pace.
5. **Ask questions** and connect with other learners via Discord.

---

## Tools & Setup

Make sure you have the following installed before the first session:

- Python 3
- VS Code or JupyterLab
- NumPy, Pandas, Matplotlib, Scikit-Learn, seaborn

```bash
# Quick install
pip install numpy pandas matplotlib scikit-learn seaborn jupyterlab
```

📺 **[Watch the environment setup guide →](#)** *(added after Session 1)*

---

## Learning Outcomes

By the end of this course, you will be able to:

| # | Outcome |
|---|---------|
| CLO 1 | Explain fundamental ML concepts, terminology, and categories and their relevance to AI |
| CLO 2 | Implement data preprocessing, feature engineering, and complete ML workflows using Python |
| CLO 3 | Apply classical ML algorithms (regression, classification, clustering, SVMs, ensembles) |
| CLO 4 | Interpret model outputs, visualizations, and feature importances |
| CLO 5 | Evaluate models using appropriate metrics (accuracy, F1, cross-validation, etc.) |
| CLO 6 | Implement design strategies to promote ethical and responsible AI |

---

## Weekly Schedule

> 🎥 **Recordings** and 📑 **Slides** are linked after each session.

### Stage 1 — The ML Landscape & Foundations

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 1 | Ch. 1 – The ML Landscape | Introduction to ML, types of ML, real-world applications, environment setup | **Lab 1:** Environment setup + "Hello ML World" (toy dataset) | 📑 Slides | 🎥 Recording |
| 2 | Ch. 1 (cont.) | Key terminology, model vs. algorithm, supervised vs. unsupervised, data representation | **Exercise:** Explore Iris dataset; visualize decision boundaries | 📑 Slides | 🎥 Recording |

---

### Stage 2 — End-to-End ML Projects & Data Preparation

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 3 | Ch. 2 – End-to-End ML Project | The ML pipeline, loading data, train/test splits, basic model training | **Lab 2:** End-to-end project with Boston/housing dataset | 📑 Slides | 🎥 Recording |
| 4 | Ch. 2 (cont.) | Data cleaning, EDA, missing values, Pandas, correlation matrices | **Mini Project 1:** Custom EDA report with visualizations | 📑 Slides | 🎥 Recording |

---

### Stage 3 — Classification

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 5 | Ch. 3 – Classification | Binary vs. multiclass, logistic regression, k-NN, confusion matrix, precision/recall/F1 | **Lab 3:** Build a classifier for handwritten digits | 📑 Slides | 🎥 Recording |
| 6 | Ch. 3 (cont.) | k-fold cross-validation, bias-variance tradeoff, TF-IDF for text | **Assignment 1:** Classify spam emails using TF-IDF features | 📑 Slides | 🎥 Recording |

---

### Stage 4 — Training Models

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 7 | Ch. 4 – Training Models | Linear regression, gradient descent, from-scratch vs. Scikit-Learn | **Lab 4:** Compare SGD vs. Normal Equation solutions | 📑 Slides | 🎥 Recording |
| 8 | Ch. 4 (cont.) | Polynomial regression, overfitting/underfitting, Ridge & Lasso regularization | **Mid-term Assessment:** Concept quiz + short coding test | 📑 Slides | 🎥 Recording |

---

### Stage 5 — Advanced Algorithms

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 9 | Ch. 5 – Support Vector Machines | Max-margin, kernel trick, SVM classification & regression, hyperparameter tuning | **Lab 5:** Tune kernel and regularization parameters | 📑 Slides | 🎥 Recording |
| 10 | Ch. 6 – Decision Trees | Tree construction, information gain, feature importance, tree vs. linear models | **Lab 6:** Tree vs. Linear model on same dataset | 📑 Slides | 🎥 Recording |
| 11 | Ch. 7 – Ensemble Methods | Bagging, Random Forests, Boosting, bias-variance improvement | **Mini Project 2:** Compare ensemble methods on tabular data | 📑 Slides | 🎥 Recording |

---

### Stage 6 — Dimensionality Reduction & Unsupervised Learning

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 12 | Ch. 8 – Dimensionality Reduction | PCA, manifold learning, visualizing high-dimensional data | **Lab 7:** PCA on image data (e.g., faces) | 📑 Slides | 🎥 Recording |
| 13 | Ch. 9 – Unsupervised Learning | k-means, DBSCAN, hierarchical clustering, embeddings | **Lab 8:** Customer segmentation or document clustering | 📑 Slides | 🎥 Recording |

---

### Stage 7 — Integration, Projects & Ethics

| Week | Chapter | Key Topics | Lab / Assignment | Slides | Recording |
|------|---------|-----------|-----------------|--------|-----------|
| 14 | Review & Integration | Complete ML pipelines, model comparison & selection, metric-based justification | **Assignment 2:** Build a full end-to-end ML pipeline | 📑 Slides | 🎥 Recording |
| 15 | Project Work | Capstone: apply the pipeline to a chosen dataset; debug, document, peer feedback | **Final Project:** Dataset + report + presentation | 📑 Slides | 🎥 Recording |
| 16 | Presentations & Wrap-Up | Student presentations, ethical AI, identifying bias, responsible AI strategies | **Final Demo & Peer Review** | 📑 Slides | 🎥 Recording |

---

## Resources

### Primary Textbook
- 📘 Aurélien Géron, *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*, 3rd Edition — [O'Reilly](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) | [GitHub Notebooks](https://github.com/ageron/handson-ml3)

### Supplementary
- 📗 [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — Jake VanderPlas (free online)
- 📙 [Python for Data Analysis](https://wesmckinney.com/book/) — Wes McKinney (free online)
- 🔢 [100 NumPy Exercises](https://github.com/arewadataScience/ArewaDS-Machine-Learning/blob/main/100_numpy_exercise.md)
- 🐼 [Pandas Exercises](https://github.com/guipsamora/pandas_exercises)

---

## Community & Contact

| Platform | Link |
|---------|------|
| 🌐 Website | [arewadatascience.github.io](https://arewadatascience.github.io) |
| 💬 Discord | [Join our Discord](https://discord.gg/gg6ntVcgVf) |
| 📧 Email | arewadatascience@gmail.com |
| 🐦 Twitter/X | [@arewadatascience](https://twitter.com/arewadatascience) |
| 💼 LinkedIn | [ArewaDataScience](https://www.linkedin.com/company/arewadatascience) |
| 📺 YouTube | [ArewaDS Academy](https://www.youtube.com/@arewadatascienceacademy7195/videos) |
| ✈️ Telegram | [Join Telegram](https://t.me/+vGZvQdggp1A4NzNk) |

---

> **ArewaDataScience** — Building Africa's data science talent, one session at a time.  
> All materials are free and open. Share freely. 🌍
