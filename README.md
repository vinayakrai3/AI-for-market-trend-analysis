# AI for Market Trend Analysis  
### Short-Term Stock Trend Prediction using NVIDIA (NVDA)

## Overview
This repository contains an academic project focused on applying basic artificial intelligence techniques to analyze stock market trends. Using historical daily price data of NVIDIA (NVDA) from the past five years, the project formulates market trend prediction as a binary classification problem that aims to predict whether the stock price will move upward or downward on the following trading day.

The project is intended for educational purposes and demonstrates a complete, end-to-end machine learning workflow for market trend analysis.

---

## Primary Evaluation Artifact
- **`notebook.ipynb`**  
  This Jupyter Notebook is the **primary and authoritative evaluation artifact** for the project.  
  It includes:
  - Problem definition and motivation
  - Data collection and preprocessing
  - Feature engineering using technical indicators
  - Model design, training, and evaluation
  - Edge case analysis
  - Ethical considerations
  - Conclusion and future scope

The notebook is designed to run **top-to-bottom without errors**.

---

## Dataset Information
- **Source:** Yahoo Finance (accessed via `yfinance`)
- **Stock:** NVIDIA Corporation (NVDA)
- **Frequency:** Daily data
- **Time Period:** Last 5 years

The dataset is downloaded programmatically within the notebook; no external data files are required.

---

## Methodology Summary
- Supervised machine learning (binary classification)
- Logistic Regression as a baseline model
- Feature engineering using:
  - Daily returns
  - Short-term moving averages (5-day, 10-day)
  - Relative Strength Index (RSI)
- Feature standardization
- Time-series-aware train–test split
- Evaluation using accuracy, confusion matrix, and ROC-AUC

---

## Results Summary
The model achieves performance slightly above random guessing when evaluated using ROC-AUC, reflecting the challenging and noisy nature of short-term financial market prediction. The results are interpreted conservatively, with emphasis on educational insight rather than real-world trading performance.

---

## External Submission Links
The following supporting artifacts are submitted as per the official guidelines:

- 📄 **Project Report (Google Docs):**  
  <PASTE GOOGLE DOCS LINK HERE>

- 📊 **Project Presentation (Google Slides):**  
  <PASTE GOOGLE SLIDES LINK HERE>

- 🎥 **Demonstration Video (Google Drive – video file link):**  
  <PASTE GOOGLE DRIVE VIDEO FILE LINK HERE>

All links are shared with permission set to **“Anyone with the link → Viewer”**.

---

## How to Run
1. Open `notebook.ipynb`
2. Run all cells sequentially from top to bottom
3. The dataset will be automatically downloaded from the internet

---

## Notes & Limitations
- This project is intended strictly for academic and educational purposes
- The model does not constitute financial or investment advice
- Market behavior is influenced by external factors not captured in this project

---

## Author
Vinayak Rai  


