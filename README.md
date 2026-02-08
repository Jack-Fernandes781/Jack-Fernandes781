<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:4ECDC4,100:45B7D1&height=200&section=header&text=Jack%20Fernandes&fontSize=50&fontColor=FFFFFF&fontAlignY=35&desc=Data%20Scientist&descSize=20&descColor=FFFFFF&descAlignY=55&animation=twinkling"/>

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=4ECDC4&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=600&height=80&lines=Predictive+Modeling+%7C+Machine+Learning;Turning+Raw+Data+Into+Real+Decisions" alt="Typing SVG" /></a>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-FF6B6B?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![Portfolio](https://img.shields.io/badge/Portfolio-4ECDC4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/Jack-Fernandes781)
[![Email](https://img.shields.io/badge/Email-45B7D1?style=for-the-badge&logo=gmail&logoColor=white)](mailto:)

</div>

<br>

<img align="right" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDVwOWF6eGxkZXRhNnBraTRhbmd4MWx5OXBhMmtiZnNheTJ1a2I5YyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" width="300"/>

## About Me

I build ML systems that solve operational problems — predicting equipment failures, forecasting hospital resource needs, and pulling insights out of data that others overlook.

My focus areas:

- **Predictive Analytics** — forecasting failures and outcomes before they cost money
- **Classification Systems** — multi-class models with real business impact
- **Data Storytelling** — making complex findings accessible to stakeholders
- **Healthcare & Operations Analytics** — turning large datasets into actionable decisions

<br clear="right"/>

---

## Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,sklearn,flask,git,github,vscode&theme=dark&perline=6" alt="Core Tools" />

<br><br>

![Pandas](https://img.shields.io/badge/pandas-FF6B6B?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-4ECDC4?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-45B7D1?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-FF6B6B?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-4ECDC4?style=for-the-badge&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-45B7D1?style=for-the-badge&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-FF6B6B?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SMOTE](https://img.shields.io/badge/SMOTE-4ECDC4?style=for-the-badge)

</div>

---

## Featured Work

<div align="center">

<a href="https://github.com/Jack-Fernandes781/fleet-predictive-maintenance">
<img src="https://img.shields.io/badge/FLEET%20PREDICTIVE%20MAINTENANCE-FF6B6B?style=for-the-badge&logoColor=white" alt="Fleet Project"/>
</a>

</div>

<details>
<summary><b>Predicts vehicle component failures 30 days out — click to expand</b></summary>
<br>

An end-to-end ML pipeline that ingests telematics data and predicts **engine**, **brake**, and **battery** failures before they strand a truck on the highway.

| What | Detail |
|------|--------|
| **Best Model** | Gradient Boosting — ~84% accuracy |
| **Business Impact** | ~64% cost reduction vs reactive maintenance |
| **Stack** | scikit-learn, SMOTE, Flask REST API, pandas |
| **Features** | 100+ engineered from rolling stats, thresholds, and interactions |

The system handles class imbalance with SMOTE, engineers rolling-window features from raw sensor data, and exposes predictions through a Flask API that fleet managers can hit in real time.

```
Estimated Savings:
  Without model:  $34,450
  With model:     $12,350
  Saved:          $22,100 (64%)
```

</details>

<br>

<div align="center">

<a href="https://github.com/Jack-Fernandes781/hospital-los-prediction">
<img src="https://img.shields.io/badge/HOSPITAL%20LOS%20PREDICTION-4ECDC4?style=for-the-badge&logoColor=white" alt="Hospital LOS Project"/>
</a>

</div>

<details>
<summary><b>Predicts hospital stay duration from 500K patient records — click to expand</b></summary>
<br>

Classification pipeline that predicts hospital length of stay categories (Short / Standard / Extended / Long) to support capacity planning and resource allocation.

| What | Detail |
|------|--------|
| **Best Model** | Gradient Boosting — 92.8% accuracy |
| **Dataset** | 500,000 patient admission records, 44 engineered features |
| **Stack** | scikit-learn, SciPy, pandas, Matplotlib, Seaborn |
| **Analysis** | Chi-square, ANOVA, Cramer's V, 16 visualizations |

Statistical analysis identified **department, gender, age, and ward** as the strongest predictors of stay duration (Cramer's V > 0.48). Three classifiers compared with full confusion matrices and feature importance analysis.

```
Model Comparison:
  Random Forest:       90.5%
  Gradient Boosting:   92.8%
  Logistic Regression: 83.5%
```

</details>

---

## How I Approach Problems

<div align="center">

```mermaid
graph LR
    A[Raw Data] -->|Clean & Validate| B[Feature Engineering]
    B -->|Train & Tune| C[Model Selection]
    C -->|Evaluate| D[Business Impact]
    D -->|Deploy| E[API / Dashboard]

    style A fill:#FF6B6B,stroke:#FF6B6B,color:#fff
    style B fill:#4ECDC4,stroke:#4ECDC4,color:#fff
    style C fill:#45B7D1,stroke:#45B7D1,color:#fff
    style D fill:#FF6B6B,stroke:#FF6B6B,color:#fff
    style E fill:#4ECDC4,stroke:#4ECDC4,color:#fff
```

</div>

---

## Currently Exploring

<div align="center">

| Area | Why |
|:----:|:---:|
| **Deep Learning** | Extending into neural nets for complex pattern recognition |
| **NLP** | Unstructured text data is everywhere and underutilized |
| **Time Series** | Better forecasting for operational and financial data |
| **MLOps** | Closing the gap between notebook and production |

</div>

---

<div align="center">

*Open to collaborating on data science projects with real-world impact.*

<br>

![Profile Views](https://komarev.com/ghpvc/?username=Jack-Fernandes781&color=4ECDC4&style=for-the-badge&label=VISITORS)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:4ECDC4,100:45B7D1&height=120&section=footer&animation=twinkling"/>
