# 🔧 Predictive Maintenance using Machine Learning

This project focuses on **Predictive Maintenance** for pressure systems using machine learning techniques.  
The goal is to predict potential failures in advance, improving reliability and reducing downtime.

---

## 📂 Project Structure

│── model/
│ ├── app.ipynb # Main notebook for training & model development
│ └── dataset.csv # (Ignored in repo, large file)
│ └── model.pkl # (Ignored in repo, trained model file)
│
│── testing/
│ ├── testing.ipynb # Notebook for testing and evaluation
│ ├── testing_dataset.csv # (Ignored in repo)
│ └── prediction_output.csv # (Ignored in repo)
│── .gitignore


---

## 🚀 Features
- Preprocessing and cleaning of dataset  
- Feature extraction and selection  
- Training with **Decision Tree Classifier**  
- Model evaluation on test dataset  
- Testing pipeline for new data  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kunwardhruv/predictive-maintenance.git
   cd predictive-maintenance
2. Create and actpython -m venv venv
venv\Scripts\activate   # For Windows
source venv/bin/activate  # For Mac/Linux
ivate virtual environment (optional but recommended):

3. Install dependencies:
pip install -r requirements.txt


4. Training

Open the notebook:

jupyter notebook model/app.ipynb

5. Testing

Run the testing notebook:
jupyter notebook testing/testing.ipynb

