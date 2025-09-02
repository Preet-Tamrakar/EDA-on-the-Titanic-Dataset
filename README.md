# AI-Powered Exploratory Data Analysis (EDA) Project

This project demonstrates how to perform **Exploratory Data Analysis (EDA)** using Python.  
It goes beyond traditional EDA by integrating a **local Large Language Model (LLM)** via **Ollama (Mistral)** to generate automated analytical insights.  
Additionally, a simple **Gradio web interface** allows users to upload their own CSV files and instantly receive both standard EDA outputs and AI-powered insights.

---

## 🚀 Features
- **Comprehensive EDA**: Data loading, summary statistics, missing value handling, and cleaning.  
- **Data Visualization**: Graphical representation of patterns using **Matplotlib** and **Seaborn**.  
- **AI-Generated Insights**: Leverages **Ollama (Mistral)** to analyze dataset summaries and provide human-like insights.  
- **Interactive Web UI**: Built with **Gradio**, enabling users to upload any CSV file and run automated EDA.  

---

## 🛠️ Technologies & Libraries Used
**Language:** Python 3.8+  

**Core Libraries:**  
- `pandas` → Data manipulation and analysis  
- `numpy` → Numerical operations  
- `matplotlib` & `seaborn` → Data visualization  

**AI & Interface:**  
- `ollama` → Connect with local LLMs (Mistral)  
- `gradio` → Build an interactive web interface  

**Environment:**  
- Jupyter Notebook  

---

## ⚙️ Setup and Installation

### 1. Prerequisites
- Python 3.8+ installed  
- **Ollama** installed and running on your system  
- Pull the Mistral model with:
  ```bash
  ollama pull mistral

---

## 📥 Clone the Repository
To get a local copy of this project on your system, run:
```bash
git clone https://github.com/your-username/eda-project.git
cd eda-project
