# Ensemble-ML-for-Cytotoxicity-PredictionPredicting nanoparticle cytotoxicity using stacked ensemble machine learning and explainable AI.  
Combines multiple algorithms (LightGBM, Random Forest, XGBoost) with SHAP and LIME to deliver accurate, interpretable toxicity classification and insights supporting safer nanomaterial design.

---

## 🧩 Overview

This project presents a **multi-model ensemble** framework for **nanoparticle toxicity prediction** based on physicochemical and biological features.  
It aims to enable fast, computational toxicity screening to assist in **nanomaterial safety** and **regulatory decision-making**.

### Key Highlights
- 🔬 **Stacked Ensemble Learning:** Combines base models using a meta-learner for improved accuracy.  
- 🧠 **Explainable AI:** SHAP and LIME visualizations for global & local interpretability.  
- ⚖️ **Imbalance Handling:** Uses SMOTE and class weights to balance toxicity categories.  
- 🧪 **Rigorous Validation:** GroupKFold and leakage prevention ensure reproducible results.  
- 📈 **Publication Quality Outputs:** Well-documented code, clean visuals, and reproducible results.

---


## 🔍 SHAP Insights (Example)

**Global importance (Top 10):**
- Particle Size (nm)  
- Zeta Potential  
- Surface Area  
- ROS Level  
- Exposure Time  


**Case Study:**  
A nanoparticle with high ROS level and large surface area predicted *toxic* because both features strongly push the SHAP value towards the “toxic” class, while small Zeta potential reduces it slightly.

---

## 🧠 Research Impact

This framework provides:
- Faster, reproducible **computational toxicity screening**  
- Data-driven **feature insights** for safe nanomaterial design  
- Explainable models for **transparent AI-driven risk assessment**

---


## 📜 License
Academic and research use only.  
For commercial or collaborative use, please contact the project maintainer.

---

## 🙌 Acknowledgments
Developed as part of a research initiative in **computational nanotoxicology**.  
Incorporates techniques from modern ensemble learning and explainable AI.

---

📧 *For questions or collaboration: [jvrhsn@gmail.com]*
