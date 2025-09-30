# NLP Experiment 2

This repository contains experiments in **Natural Language Processing (NLP)** focusing on encoding categorical data into numerical form using **scikit-learn** preprocessing techniques.

## 📌 Project Overview

The notebook (`NLP_EXP2.ipynb`) demonstrates how to apply encoding methods to transform text labels into numerical representations suitable for machine learning models.

## ⚙️ Techniques Used

* **Label Encoding** – Converts categorical text data into integer labels.
* **One-Hot Encoding** – Represents categories as binary vectors.
* **scikit-learn Preprocessing** – Utilized `LabelEncoder` and `OneHotEncoder`.

## 🛠️ Requirements

Make sure you have the following installed:

```bash
pip install numpy pandas scikit-learn jupyter
```

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/pridwimnjha/Text-Representation--Implementation.git
   cd Text-Representation--Implementation
   ```
2. Open Jupyter Notebook:

   ```bash
   jupyter notebook NLP_EXP2.ipynb
   ```
3. Run each cell sequentially to see label encoding and one-hot encoding in action.

## 📊 Example Output

* **Label Encoding:**

  ```
  ["positive", "negative", "neutral", "positive"] 
  → [2, 0, 1, 2]
  ```
* **One-Hot Encoding:**

  ```
  ["positive", "negative", "neutral"] 
  → [[1,0,0], [0,1,0], [0,0,1]]
  ```



Do you want me to also **add a section on potential applications of encoding in NLP** (like sentiment analysis, text classification, etc.) to make it look more professional?
