
# BurnOut Lite 🔥: AI-powered CPU Benchmark Estimator

BurnOut is a lightweight machine learning project that predicts standardized CPU benchmark scores based on system specifications like core/thread count, TDP, and power efficiency.  
It was developed as part of the final project submission for the AI Using Python summer training program at CDAC Mohali.

## 📌 Features

- Predicts Cinebench R23-style CPU performance score
- Dataset of 1000+ entries cleaned and labeled
- Trained with Random Forest and Linear Regression
- Correlation analysis, distribution plots, and visual insights

## 📁 Folder Structure

```
burnout-lite/
├── BurnOut Lite.ipynb
├── dataset/
│   └── CPU_benchmark_v4.csv
├── README.md
├── python_notebook_result/
│   └── BurnOut_Lite_Results.pdf
└── requirements.txt
```

## 📊 Dataset

The dataset used contains processor specs and Cinebench R23 benchmark results.  
All entries are cleaned and encoded for modeling.

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-Learn
- Matplotlib, Seaborn
- TensorFlow
- PSUtil, Py-CPUinfo
- Plotly

## 📈 Output

The model predicts benchmark scores and compares them against expected CPU classes (Desktop, Mobile, Workstation).

## 📬 Author

Manit Saxena – CDAC Mohali  
LinkedIn: [linkedin.com/in/manit-saxena](https://www.linkedin.com/in/manit-saxena)
