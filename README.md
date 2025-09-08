# Multi-Omics Biomarker Discovery using Graph Neural Networks (GNNs)

This project focuses on multi-omics biomarker discovery by integrating genomics, transcriptomics, and proteomics data into a graph-based framework. Using Graph Neural Networks (GNNs), it models complex biological interactions (genes–proteins–pathways) to:

Predict disease onset and progression (e.g., renal, cardiovascular, cancer).

Identify novel biomarkers that play a critical role in disease mechanisms.

Enable precision medicine insights by linking omics layers into one AI-driven pipeline.

Unlike traditional single-omics machine learning approaches, this project leverages heterogeneous graphs and deep learning to capture multi-level biological relationships, making it a rare and cutting-edge approach in bioinformatics.

## ✨ Key Features
- Integrates **multi-omics data** (from GEO, TCGA, STRING DB).
- Builds **heterogeneous biological graphs** (genes–proteins–pathways).
- Applies **Graph Neural Networks (PyTorch Geometric)** for disease classification.
- Outputs **potential biomarkers** ranked by importance.

---

## 📊 Data Sources
- [GEO (NCBI)](https://www.ncbi.nlm.nih.gov/geo/) – Gene expression datasets  
- [TCGA](https://www.cancer.gov/tcga) – Multi-omics cancer datasets  
- [STRING DB](https://string-db.org/) – Protein-protein interactions  
- [GTEx](https://gtexportal.org/) – Healthy control tissue expression  

---

## 🛠 Tech Stack
- **Python 3.9+**
- **PyTorch & PyTorch Geometric**
- **Scikit-learn, Pandas, NumPy**
- **Biopython**
- **Matplotlib / Seaborn**

---

## 🚀 Setup

```bash
# Clone repo
git clone https://github.com/nikhil1111111/multi-omics-GNN-biomarker-discovery.git
cd multi-omics-GNN-biomarker-discovery

# Create environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install requirements
pip install -r requirements.txt
