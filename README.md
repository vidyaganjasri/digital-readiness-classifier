# digital-readiness-predictor
In today's fast-paced digital world, assessing a country's readiness for digital transformation is critical for effective policy-making and strategic investments. Traditional methods are manual, slow, and lack predictive power. This project was built to solve that — by using machine learning to automatically classify whether a country is **Digitally Ready** or **Not Ready**, based on realistic socio-economic and telecom indicators from 2010 to 2025.

Our goal was to build a **scalable, interpretable, and highly accurate tool** that can:
- Help governments identify digitally lagging regions
- Guide infrastructure rollout decisions (like 5G)
- Support researchers and planners with actionable digital maturity insights

---

## Project Overview

This project predicts the digital transformation readiness of countries using a synthetic dataset (2010–2025) with features like internet penetration, broadband speed, GDP, education level, and digital investment.

### Key Steps:
1. Preprocessing & Labeling using Digital Readiness Score (DRS)
2. Model: Random Forest Classifier
3. Evaluation: Accuracy = 97.5%, F1 Score = 0.9796
4. Top Features: Broadband Speed, Internet Penetration, Mobile Usage

---

## Architecture Diagram
<img width="523" height="362" alt="image" src="https://github.com/user-attachments/assets/1b4eadac-18a8-4528-a759-34486077e83b" />

---

## Visualizations

### 🔹 Histogram of Features
![Histogram](histogram.png)

### 🔹 Urban vs Rural Internet Penetration
<img width="791" height="467" alt="image" src="https://github.com/user-attachments/assets/66976b3b-9496-43d3-af54-4442acbd7afc" />

---

## Performance Metrics

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | 97.5%     |
| Precision      | 1.00      |
| Recall         | 0.96      |
| F1 Score       | 0.9796    |

---

## Feature Importances

| Rank | Feature                   | Importance |
|------|---------------------------|------------|
| 1    | Broadband Speed (Mbps)    | 0.237      |
| 2    | Internet Penetration (%)  | 0.234      |
| 3    | Mobile Data Usage (GB)    | 0.158      |
| 4    | Digital Literacy (%)      | 0.138      |
| 5    | Digital Investment (M USD)| 0.087      |

---

## Tools & Technologies
- Python 3.x, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- Platform: Google Colab (CPU only)

---
