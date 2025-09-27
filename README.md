# Resume-analyzer-NLP 📝
Automated Resume Screener &amp; Interview Question Generator                                                                                  
This project is specially designed for Data Scientist related resumes this is just a try
It is a self-intiated project to demonstrate my skills in Natural Language Processing (NLP),Machine Learning (ML) and LLM's   
## ✨Key Features
- **DS/Non-DS Classification**: Uses **TF-IDF vectorization** and **Logistic Regression** to classify resumes with high accuracy.  
- **Interview Question Generation**: Integrates a **locally hosted LLaMA 2 model** to automatically generate 5 role-specific interview questions per resume.  
- **Model Evaluation & Visualization**:  
  - Confusion Matrix  
  - ROC Curve & AUC  
  - Feature Importance Analysis  
---

## 💻Technologies Used
- **Python**: Core programming  
- **scikit-learn**: TF-IDF, Logistic Regression, evaluation metrics  
- **pandas / numpy**: Data manipulation  
- **matplotlib / seaborn**: Visualization  
- **ctransformers / LLaMA 2**: Local language model for interview question generation  

---


## 🚀Getting Started

Follow these steps to run the Resume Analyzer NLP project locally or in Google Colab.


### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Arch070/Resume-analyzer-NLP.git
cd Resume-analyzer-NLP



2️⃣ Install Required Libraries

python -m venv venv
source venv/bin/activate      # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt

3️⃣ Run the Notebook

Open the Jupyter notebook:
jupyter notebook resume.ipynb







