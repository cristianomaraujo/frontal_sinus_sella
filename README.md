# Machine Learning for Sex Prediction Using Anterior Cranial Measurements

This repository provides the source code developed for a study investigating the application of **machine learning techniques to craniofacial morphometric data** for biological sex prediction.

The project uses measurements derived from **lateral cephalometric radiographs**, focusing on anatomical structures of the **anterior cranial region**, including the frontal sinus and the anterior cranial base.

The goal of this repository is to ensure **computational transparency and reproducibility** of the analytical workflow implemented in the study.

---

# Project Background

Determining biological sex is one of the essential steps in **forensic human identification**, particularly when skeletal remains are incomplete or fragmented. Although the pelvis and long bones are typically considered the most reliable indicators, these structures are not always preserved.

Cranial anatomy represents an important alternative source of information due to its **structural resilience and morphological variability**. Several craniofacial structures have been explored for this purpose in forensic research.

In this project, morphometric measurements from the **anterior cranial region** were used as predictors in machine learning models designed to classify individuals according to sex.

---

# Study Aim

The main objective of this work is to explore the use of **supervised machine learning algorithms** to classify individuals based on morphometric features extracted from lateral cephalometric radiographs.

More specifically, the project seeks to:

* evaluate the predictive capacity of measurements from the anterior cranial region
* implement and compare multiple machine learning algorithms
* establish a transparent and reproducible computational pipeline

---

# Craniofacial Measurements Used

The dataset includes morphometric variables obtained from lateral cephalometric radiographs:

* **Frontal sinus height (mm)**
  Maximum vertical dimension of the frontal sinus.

* **Frontal sinus width (mm)**
  Maximum horizontal dimension of the frontal sinus.

* **Frontal sinus area (mm²)**
  Total sinus area as visualized in the radiographic projection.

* **Sella–nasion distance (mm)**
  Linear measurement between the sella turcica and nasion landmarks, representing the anterior cranial base length.

---

# Machine Learning Pipeline

The computational workflow implemented in this project follows several stages:

1. **Data preparation**
   Organization and preprocessing of morphometric variables.

2. **Model development**
   Training of supervised machine learning algorithms.

3. **Hyperparameter tuning**
   Optimization of model parameters using systematic search strategies.

4. **Cross-validation**
   Internal validation procedures to assess model stability.

5. **Independent testing**
   Evaluation of model performance using a separate test dataset.

6. **Performance assessment**
   Calculation of classification metrics to evaluate predictive performance.

7. **Bootstrap analysis**
   Estimation of confidence intervals for model performance metrics.

---

# Repository Structure

```
├── data
│   Dataset used for model training and evaluation
│
├── notebooks
│   Scripts and notebooks containing the machine learning pipeline
│
├── figures
│   Visual outputs generated during the analysis
│
├── models
│   Saved model objects and prediction outputs
│
└── README.md
```

---

# Software Environment

The analyses were performed using **Python 3.10** within the scientific Python ecosystem.
Key libraries include:

* **scikit-learn** – machine learning algorithms and model evaluation
* **NumPy** – numerical computing
* **Pandas** – data manipulation
* **Matplotlib** – data visualization
* **SciPy** – statistical routines

---

# Reproducibility

This repository contains the complete analytical pipeline used in the study, including:

* data preprocessing procedures
* machine learning model training
* hyperparameter optimization
* model validation and evaluation

Providing access to the full codebase allows independent verification and facilitates the reproducibility of the analytical procedures.

---

# License

This repository is intended for **academic and research purposes**.

