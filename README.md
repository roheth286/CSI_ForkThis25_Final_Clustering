# ⚙️ Clustering of Sensorless Drive Diagnosis 📊

## 🎯 Project Goal  
This dataset comprises features derived from motor current signals. The motor operates under **11 distinct conditions** representing combinations of intact and defective components. Each condition is measured across **12 different operating scenarios**, varying in speed, load moments, and load forces. The current signals were captured using a probe and oscilloscope on **two phases**. The dataset does not explicitly indicate which conditions are defective or intact.  

To investigate the underlying structure and patterns within the data, **clustering algorithms** are applied. Using unsupervised techniques, we aim to uncover natural groupings of motor conditions, potentially distinguishing defective from intact components, and understand how different operating setups affect the recorded signal features.

---

## 🔬 Project Overview  
We provide a complete clustering pipeline for exploratory and diagnostic analysis:  
- 📂 Data loading and preprocessing  
- 🔽 Dimensionality reduction  
- 🤖 Multiple clustering algorithms  
- 📊 Cluster evaluation (internal metrics and label-based measures)  
- 🌟 Feature importance  
- 🖼️ Visualizations for interpretation  

---

## 📊 Dataset  
- **Size:** 58,509 samples  
- **Features:** 48 columns per sample (last column is the class label)  

---

## 📁 Project Structure  
1. `README.md` → You are here (start by reading this file 👀)  
2. `.ipynb` → The main notebook (complete pipeline)  
3. `.txt` → Dataset file  

---

## ⚙️ Setup  

It is recommended that the notebook is run in Google Colab, although if you want, you can run it locally as well.

For local setup, follow these steps to set up your environment and install project dependencies:

## Clone the repository
```
git clone https://github.com/<your-username>/CSI_ForkThis25_Final_Clustering.git
```

## Navigate to the project directory
```
cd CSI_ForkThis25_Final_Clustering
```

## Create a virtual environment (recommended)
```
python -m venv venv
```

## Activate the virtual environment
## On Windows:
```
#First run:
cd venv/Scripts

#Then:
./Activate.ps1
```

## On macOS and Linux:
```
#First run:
cd venv/bin

#Then:
source ./activate
```

## Install project dependencies from requirements.txt
```
pip install -r requirements.txt
```

