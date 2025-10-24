# AI4I 2020 Machine Failure Prediction 🔧⚙️

This project focuses on **Predictive Maintenance** using the **AI4I 2020 Industrial Dataset**, which includes real manufacturing sensor data.  
Goal: **Predict whether a machine is going to fail** based on operational conditions such as temperature, torque, rotational speed, and tool wear.

---

## 📊 Dataset Information

The dataset includes:
- **10,000 records**
- Real industrial sensor measurements
- Various failure modes from CNC milling operations

### ✅ Key Features
| Feature | Description |
|--------|-------------|
| Air temperature [K] | Environmental temperature |
| Process temperature [K] | Internal process heat |
| Rotational speed [rpm] | Machine spindle speed |
| Torque [Nm] | Load applied during machining |
| Tool wear [min] | Usage time of cutting tool |
| Type | Product category (L, M, H) |
| Machine failure | ✅ Target label |

### ⚠ Machine Failure Sub‑labels (not used directly in features)
| Column | Meaning |
|--------|---------|
| TWF | Tool Wear Failure |
| HDF | Heat Dissipation Failure |
| PWF | Power Failure |
| OSF | Overstrain Failure |
| RNF | Random Failure |

These sub‑failures are rare → **Imbalanced Dataset Problem**

---

## 🧠 Methodology

| Step | Description |
|------|-------------|
| Data Cleaning & Encoding | Convert categorical columns → numeric |
| Feature Selection | Remove identifiers (UDI, Product ID) |
| Train/Test Split | Stratified split for fair evaluation |
| Imbalance Handling | SMOTE oversampling |
| Scaling | Standardization for linear models |
| Model Training | Logistic Regression + Random Forest |
| Evaluation | F1-score, Recall, ROC-AUC, Confusion Matrix |

---

## 🚀 Models Included

| Model | Strength |
|------|----------|
| Logistic Regression | Strong interpretability |
| Random Forest | Handles nonlinear relationships well |

We evaluate **Recall of Machine Failure** as priority ✅  
(Real industrial cases focus on avoiding missed failures!)

---

## 📈 Evaluation Metrics

We avoid relying on **accuracy** due to class imbalance.  
Instead, we report:

✔ Precision  
✔ Recall  
✔ F1-score  
✔ ROC-AUC  
✔ Confusion Matrix  

---

## 🗂 Files Included

| File | Description |
|------|-------------|
| `AI4I_ML_Notebook.ipynb` | Full ML workflow implementation |
| `requirements.txt` | Required libraries |
| `README.md` | Project documentation |

---

## ▶ How to Run

```bash
pip install -r requirements.txt
jupyter notebook AI4I_ML_Notebook.ipynb
```

---

## ✅ Future Improvements (To-Do)

- Add XGBoost / LightGBM for better recall on minority class
- Hyperparameter tuning
- Feature importance visualization
- SHAP model interpretability
- Deployment as a real-time ML service
- 📌 For industrial predictive maintenance automation 🚀
