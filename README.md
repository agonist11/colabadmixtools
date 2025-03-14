# **ColabADMIXTOOLS - Quickstart Tutorial**

## **About This Repository**
Welcome to **ColabADMIXTOOLS**, a tutorial designed to help users efficiently run **ADMIXTOOLS** in **Google Colab**. This repository includes a step-by-step **Interactive Python Notebook (.ipynb)** and a **detailed Quickstart Guide (PDF)** for users interested in population genetics, ancestry modeling, and admixture analysis using the AADR dataset.

## **What is ADMIXTOOLS?**
[ADMIXTOOLS](https://uqrmaie1.github.io/admixtools/) is a powerful set of tools for analyzing genetic data, commonly used in academic research and personal ancestry studies. This repository focuses on using **qpAdm**, **qpGraph**, and other utilities to model genetic ancestry with publicly available datasets.

Additionally, this tutorial incorporates both the **original ADMIXTOOLS** developed by the [DReichLab](https://github.com/DReichLab/AdmixTools) and the **updated R-based ADMIXTOOLS2** by [uqrmaie1](https://uqrmaie1.github.io/admixtools/).

---

## **📜 Contents of This Repository**

[![Open Stable Tutorial Version 4.8a in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agonist11/colabadmixtools/blob/main/Test_ColabADMIXTOOLS_V4_8a.ipynb) Open Stable Tutorial Version 4.8a in Colab

[![Open Experimental Tutorial Version 5.0 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agonist11/colabadmixtools/blob/main/Experimental_ColabADMIXTOOLS_V5_0.ipynb) Open Experimental Tutorial Version 5.0 in Colab.

### **🔹 Files Included**
- **📄 [Test_ColabADMIXTOOLS_V4_8a.ipynb](https://github.com/agonist11/colabadmixtools/blob/main/Test_ColabADMIXTOOLS_V4_8a.ipynb)** – The interactive Python notebook for running ADMIXTOOLS.
- **📘 [ColabADMIXTOOLS Quickstart Guide 2nd Edition (PDF)](https://github.com/agonist11/colabadmixtools/blob/main/ColabADMIXTOOLS%20Quickstart%20Guide%202nd%20Edition_Draft3.pdf)** – A comprehensive guide explaining installation, dataset selection, and model interpretation.

### **🔹 Quick Links**
- **📌 Open the Notebook in Colab:** [Google Colab Link](https://colab.research.google.com/) *(Upload the `.ipynb` file to start the tutorial)*  
- **📖 View the Quickstart Guide:** [Download PDF](https://github.com/agonist11/colabadmixtools/blob/main/ColabADMIXTOOLS%20Quickstart%20Guide%202nd%20Edition_Draft3.pdf)  

---

## **🚀 Getting Started**

### **1️⃣ Open the Colab Notebook**
1. Go to **Google Colab** → [colab.research.google.com](https://colab.research.google.com/)
2. Click on **"Upload Notebook"** and select `Test_ColabADMIXTOOLS_V4_8a.ipynb`
3. Change the **runtime type** to `"Python 3"` (default).

### **2️⃣ Install Required Packages**
Run the first cell in the notebook to install **ADMIXTOOLS**, **PLINK**, and **rpy2** (for R support).

### **3️⃣ Load Genetic Data**
You will need a dataset to analyze. Follow the Quickstart Guide for instructions on:
✅ Uploading your own **23andMe**, **AncestryDNA**, or **MyHeritage** files  
✅ Downloading and merging datasets from **AADR**

### **4️⃣ Run qpAdm Analysis**
The tutorial walks you through using qpAdm to model admixture. Follow the step-by-step sections in the **Colab Notebook** or **PDF Guide** to set up your **Left**, **Right**, and **Target** populations.

---

## **📂 Features and Tools**
This tutorial covers essential topics for analyzing ancient and modern genetic data:

📌 **qpAdm Modeling** – Estimate ancestry proportions using a reference population set.  
📌 **Hudson's Fst Analysis** – Measure genetic differentiation between populations.  
📌 **Population Merging** – Integrate your own DNA with public datasets.  
📌 **Admixture Graphs** – Visualize ancestry models in tree-like structures.  
📌 **Principal Component Analysis (PCA)** – Compare genetic similarities.  

For details, refer to the **Documentation Links** provided in the **Quickstart Guide (PDF)**.

---

## **🔧 Troubleshooting**
- **Colab Crashed?** → Restart runtime and reinstall dependencies.  
- **Low p-value in qpAdm?** → Adjust the Right pops or rotate models.  
- **Issues with dataset merging?** → Ensure correct formatting and overlap with AADR.  

---

## **📝 Acknowledgements**
Special thanks to **Florio** and the community for contributions, testing, and documentation.

---

### 📥 **Clone This Repository**
```sh
git clone https://github.com/agonist11/colabadmixtools.git
```

## **📜 License**
This Colab notebook tutorial is licensed under **CC BY-NC 4.0**, allowing modifications and sharing for **non-commercial purposes only**.

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

You can view the full license in the [`LICENSE`](LICENSE) file.
