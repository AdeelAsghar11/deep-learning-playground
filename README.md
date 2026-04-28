# 🧠 Deep Learning Playground

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)

A personal deep learning lab — hands-on notebooks covering optimization algorithms, regularization techniques, sequence models, NLP, and medical imaging. Built as a structured practice track alongside the **CampusX 100 Days of Deep Learning** course.

> These are not polished projects — they are deliberate experiments. Every notebook was written to understand *why* something works, not just that it does.

---

## 📂 Notebooks

### ⚙️ Optimization Algorithms
Implementing classical metaheuristic optimization from scratch to build intuition about search strategies beyond gradient descent.

| Notebook | Description |
|----------|-------------|
| `Genetic_Algorithm.ipynb` | Genetic algorithm from scratch — selection, crossover, mutation on a benchmark function |
| `Simulated_Annealing_using_Python.ipynb` | Simulated annealing with temperature scheduling — applied to discrete optimization |

---

### 🛡️ Regularization Techniques
Deep dives into training stability and generalization — understanding what these techniques actually do at the gradient level.

| Notebook | Description |
|----------|-------------|
| `batch_norm.ipynb` | Batch normalization — internal covariate shift, running stats, inference vs training mode |
| `dropout_notebook.ipynb` | Dropout as approximate Bayesian inference — effect on training curves and weight distributions |

---

### 🔄 Sequence Models & RNNs
Building sequence models progressively — from raw integer encoding to stacked RNNs — before moving to LSTMs.

| Notebook | Description |
|----------|-------------|
| `integer_encoding_simplernn.ipynb` | Integer encoding pipeline + SimpleRNN on toy sequence data |
| `sentiment_analysis_simplernn.ipynb` | Sentiment classification using SimpleRNN — IMDB-style binary classification |
| `sentiment_analysis_amazondata.ipynb` | Sentiment analysis on Amazon product reviews — preprocessing + RNN baseline |

---

### 💬 NLP & LSTM
Applying LSTMs to real-world text classification problems.

| Notebook | Description |
|----------|-------------|
| `emotion_detection_text_ML_LSTM.ipynb` | Multi-class emotion detection from text using LSTM — tokenization, padding, embedding |
| `twitter_sentiment_analyss.ipynb` | Twitter sentiment classification — handling noisy social media text, class imbalance |

---

### 🏥 Medical Imaging & Hyperparameter Tuning
Computer vision applied to clinical data; automated hyperparameter search.

| Notebook | Description |
|----------|-------------|
| `keras_medical_tumor_classification.ipynb` | CNN for brain tumor classification on MRI data — transfer learning + fine-tuning |
| `keras_hp_tuner_sonarmine_dataset.ipynb` | Keras Tuner (Hyperband) on Sonar/Mine dataset — automated architecture search |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| TensorFlow / Keras | Model building and training |
| NumPy / Pandas | Data handling |
| Scikit-learn | Preprocessing, metrics |
| Matplotlib / Seaborn | Training curves and visualizations |
| Google Colab | GPU-accelerated training environment |

---

## 🚀 Running Any Notebook

All notebooks are self-contained and runnable on Google Colab or locally.

```bash
git clone https://github.com/AdeelAsghar11/deep-learning-playground.git
cd deep-learning-playground
pip install tensorflow numpy pandas matplotlib scikit-learn
jupyter notebook
```

Or open directly in Colab — click any `.ipynb` file on GitHub and hit the **Open in Colab** button.

---

## 📌 Related Projects

These notebooks feed directly into production-level projects:

- 🔍 [ThreatLens](https://github.com/AdeelAsghar11/ThreatLens) — Malware classifier using ResNet50 (from CV experiments here)
- 🩺 [DermVision](https://github.com/AdeelAsghar11/dermvision) — Skin lesion classifier using MobileNetV2
- 🤟 [BSL Hand Gesture Recognition](https://github.com/AdeelAsghar11/BSL-Hand_Gesture_Recognition) — 95.74% accuracy, live demo
