# 🧬 DNA Sequence Analysis Toolkit

This project provides a set of Python scripts for performing fundamental bioinformatics tasks on DNA sequences. It includes analysis of a single sequence (nucleotide counts, GC content, transcription, and translation) and a comparative analysis of multiple sequences.

The core analysis is performed within a Jupyter Notebook (`dna_seq.ipynb`).

---

## 🔬 Features

- **Nucleotide Counting:** Counts the occurrences of Adenine (A), Thymine (T), Guanine (G), and Cytosine (C).
- **GC Content Calculation:** Determines the percentage of Guanine and Cytosine bases.
- **Transcription:** Converts DNA to its corresponding RNA sequence (T → U).
- **Translation:** Translates the RNA sequence into a protein (amino acid) sequence using a standard codon table.
- **Visualization:** Generates bar and pie charts to visualize nucleotide composition and GC content comparison across multiple samples using `matplotlib`.

---

## 💻 Prerequisites

To run this project, you need **Python 3** and the following packages installed:

- `jupyter`
- `matplotlib`

---

## 🚀 Installation & Setup

Setting up a virtual environment is recommended.

### 1. Install Python

Ensure you have Python 3.8 or above.

- **Mac/Linux:**  
  Check: `python3 --version`
- **Windows:**  
  Download from: https://www.python.org/  
  *(Check "Add Python to PATH" during installation.)*

---

## 2. Set up a Virtual Environment

Run the commands according to your OS:

### **Mac/Linux**
```bash
python3 -m venv dna_env
source dna_env/bin/activate
```

### **Windows (CMD)**
```bash
python -m venv dna_env
dna_env\Scripts\activate.bat
```

### **Windows (PowerShell)**
```powershell
python -m venv dna_env
.\dna_env\Scripts\Activate.ps1
```

You should now see `(dna_env)` in your terminal prompt.

---

## 3. Install Required Packages

With the environment activated:

```bash
pip install jupyter matplotlib
```

---

## ▶️ How to Run the Analysis

The entire analysis is performed inside the Jupyter Notebook.

### **1. Launch Jupyter Notebook**

```bash
jupyter notebook
```

This opens a browser window with the Jupyter interface.

### **2. Open and Run the Notebook**

1. Click on `dna_seq.ipynb`.
2. Choose **Cell > Run All** to execute the entire workflow  
   or run cells one-by-one using **Shift + Enter**.

### **3. Provide Input**

During execution, you will be prompted:

```
Enter a DNA sequence:
```

Enter your sequence (e.g., `atcgacgcacg`).

The notebook produces:

- Nucleotide counts and GC content  
- Transcribed RNA sequence  
- Translated protein sequence  
- Bar & pie charts  
- GC content comparison across multiple sequences  

---

## 📝 Code Structure Overview

| Step | Description | Example |
|------|-------------|---------|
| 1–5 | Basic sequence analysis | `dna_seq = input(...)` |
| 6 | Translation | `protein = ""` |
| 7–9 | Visualization | `plt.bar(...)` |
| 10–13 | Multi-sequence analysis | `dna_samples = {...}` |

You may edit the notebook to add more genes, modify sequences, or include additional bioinformatics functionality.

---

## 📂 File Included

- **dna_seq.ipynb** — Main analysis notebook

---
