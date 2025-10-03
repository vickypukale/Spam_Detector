# Spam_Detector
# 📧 Spam Detection using Active Learning

## 📌 Project Overview  
This project implements a **Spam Detection System** using **Machine Learning**.  
The system classifies SMS messages as **spam** or **ham (not spam)**.  
It uses the dataset `spam.csv` for training and evaluation.  

The project is built in **Python** with **Jupyter Notebook** (`Spam_AL_Module.ipynb`) and demonstrates:  
- Data preprocessing & text cleaning  
- Feature extraction (Bag of Words / TF-IDF)  
- Machine Learning model training  
- Active Learning strategies for improving performance  
- Evaluation using accuracy, precision, recall, and F1-score  

---

## 📊 Dataset  
- **File:** `spam.csv`  
- Contains labeled SMS messages:  
  - **ham** → Not spam  
  - **spam** → Spam messages  

---

## ⚙️ Installation & Requirements  

Make sure you have **Python 3.8+** installed. Then, install dependencies:  

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

## 🚀 Usage  

1. Clone/download this project.  
2. Place the dataset (`spam.csv`) in the project folder.  
3. Open the Jupyter Notebook:  

```bash
jupyter notebook Spam_AL_Module.ipynb
```

4. Run all cells to:  
   - Preprocess dataset  
   - Train the spam detection model  
   - Evaluate performance  

---

## 📈 Results  

- The model successfully classifies spam vs ham messages.  
- Performance metrics include:  
  - Accuracy:  99.14%
  - Precision: 96.79%  
  - Recall: 96.79% 
  - F1-score: 96.79% 


---

## 🔮 Future Improvements  

- Deploy the model as a **Flask/Django API**  
- Build a **Streamlit Web App** for user input  
- Use **deep learning models (LSTMs, Transformers)** for better accuracy  
- Improve active learning loop for real-world adaptability  

---

## 📂 Project Structure  

```
📁 Spam-Detection-Project
│── Spam_AL_Module.ipynb   # Jupyter Notebook with implementation
│── spam.csv               # Dataset (SMS spam collection)
│── README.md              # Documentation
```
