# Eye Disease Classification using Deep Learning and NLP Techniques

This project is designed to classify eye diseases using image data and related patient information. The analysis involves Natural Language Processing (NLP), image processing, data visualization, and Machine Learning (ML)/Deep Learning (DL) techniques.

---

## 🧠 Project Goal

To detect and classify eye diseases such as:

- Normal (N)
- Diabetes (D)
- Glaucoma (G)
- Cataract (C)
- Age-related Macular Degeneration (A)
- Hypertension (H)
- Pathological Myopia (M)
- Other diseases/abnormalities (O)

---

## 🛠️ Prerequisites

Before running the notebook, ensure you have the following installed:

```bash
pip install numpy pandas matplotlib seaborn nltk wordcloud opencv-python scikit-learn tensorflow
```

## 🔁 Workflow

The workflow of the project can be divided into the following steps:

### 1. Library Installation and Imports
- Import essential libraries for data manipulation, visualization, NLP, and ML/DL models.

### 2. Dataset Preparation
- Load image and associated metadata/textual data.
- Preprocess image data using OpenCV.
- Clean and tokenize text data using NLTK.

### 3. Exploratory Data Analysis (EDA)
- Visualize class distribution.
- Plot word clouds for text data.
- Use `seaborn` and `matplotlib` to explore correlations and patterns.

### 4. Feature Engineering
- Extract features from images (e.g., edges, texture).
- Convert text into numerical features (TF-IDF or word embeddings).

### 5. Model Training
- Apply traditional ML models (e.g., Random Forest, SVM).
- Train Deep Learning models (e.g., CNN for images, RNN/LSTM for text).

### 6. Model Evaluation
- Evaluate models using accuracy, confusion matrix, precision/recall/F1-score.
- Compare different approaches and log results.

### 7. Visualization
- Plot training history (accuracy/loss curves).
- Display confusion matrices and misclassified examples.


### 📧 Contact
Developed by **Vipin Tomer**
- 📧 Email: [tvipin8171@gmail.com]
- 🏫 IIITDM Kurnool
