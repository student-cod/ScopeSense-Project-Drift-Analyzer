# ScopeSense-Project-Drift-Analyzer

ScopeSense is an NLP-powered application that detects **project scope drift** by comparing original requirements with current implementation updates.  
It translates complex semantic analysis into **human-readable insights** and **downloadable audit reports**, making it useful for both technical and non-technical stakeholders.

---

##  Live Demo
🔗 **Deployment Link: https://scopesense.onrender.com**  


---

##  Project Overview

In real-world projects, requirements often change over time, leading to **scope creep**, **technology drift**, or even complete project pivots.

ScopeSense helps answer:
- *“Are we still building what we initially planned?”*
- *“How much has the project changed?”*
- *“Is the change minor or critical?”*

The system analyzes text semantically using NLP models and generates:
- Drift classification
- Confidence levels
- Human-friendly explanations
- Professional PDF reports

---

## Tech Stack

### Languages & Frameworks
- **Python**
- **Gradio** (UI & Deployment)

### NLP & ML
- **Sentence Transformers (all-MiniLM-L6-v2)**
- **Cosine Similarity**
- **Jaccard Similarity**
- **Euclidean Distance**

### Libraries
- `sentence-transformers`
- `torch`
- `nltk`
- `scikit-learn`
- `reportlab`
- `gradio`

---

## Features

- **Semantic Requirement Comparison**
-  **Multiple Similarity Metrics**
-  **Drift Type Detection**
  - Technology Drift
  - Feature Drift
  - Critical Scope Pivot
- **Human-Friendly Explanations**
- **Downloadable PDF Report**
- **Confidence Scoring**
- **Interactive Gradio Dashboard**

---

## Sample Inputs

### Technology Drift
**Original:**  
> Build a web-based dashboard.

**Current:**  
> Developed a mobile app for iOS.

**Output:**  
- Drift: Technology Drift
- Alignment: Low

---

### Feature Drift
**Original:**  
> Track inventory levels.

**Current:**  
> Track inventory and generate sales forecasts.

**Output:**  
- Drift: Feature Drift
- Alignment: Moderate

---

### Critical Pivot
**Original:**  
> Build a delivery robot.

**Current:**  
> Develop an AI-based medical diagnosis system.

**Output:**  
- Drift: Critical Scope Pivot
- Alignment: Low

---

## How to Run Locally

### 1. Clone the repo
git clone https://github.com/<username>/ScopeSense-Project-Drift-Analyzer.git
cd ScopeSense-Project-Drift-Analyzer

### 2. Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

### 3️. Install dependencies
pip install -r requirements.txt

### 4️. Run the app
python app.py


Open browser:

http://127.0.0.1:7860
git clone https://github.com/<username>/ScopeSense-Project-Drift-Analyzer.git
cd ScopeSense-Project-Drift-Analyzer
