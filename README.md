 ## 🐊 LeatherLens – AI for Ethical Fashion & Wildlife Protection

LeatherLens is an AI-based leather texture classification system designed to promote transparency in the exotic leather trade. It helps identify whether a leather product belongs to regulated or exotic species using image-based texture analysis.

The project combines traditional texture descriptors and deep learning features to build a robust hybrid classification model.

---

## 🎯 Problem Statement

Exotic leather products are widely used in luxury fashion. However, consumers often cannot distinguish between regulated species and non-exotic leather visually. This lack of transparency contributes to illegal wildlife trade and uninformed purchasing decisions.

LeatherLens aims to bridge this gap using AI-powered texture classification.

---

## 🧠 Model Architecture

The system uses a hybrid feature extraction pipeline:

* Local Binary Patterns (LBP) – captures fine-grained texture details
* Gray Level Co-occurrence Matrix (GLCM) – captures spatial pixel relationships
* Gabor Filters – captures directional and frequency patterns
* EfficientNetB0 (CNN embeddings) – captures deep visual features

These features are fused and processed using:

* StandardScaler (feature normalization)
* PCA (dimensionality reduction)
* XGBoost (multi-class classification)

---

## 📊 Model Evaluation

The model is evaluated using:

* Precision
* Recall
* F1-score
* Confusion Matrix
* PCA Variance Retention Analysis

The hybrid approach improves classification robustness and reduces class bias.

---

## 🖥️ Tech Stack

### Frontend

* React 18 + TypeScript
* Tailwind CSS
* Vite 5
* Framer Motion
* PWA Support (vite-plugin-pwa)
* Netlify (Deployment)
* i18next & react-i18next
* React-router-dom v6

### Backend

* Python
* Flask
* OpenCV
* Scikit-learn
* Scikit-image
* XGBoost
* TensorFlow / Keras
* Render (Deployment)

---

## 🌍 Social Impact

LeatherLens supports:

* Wildlife conservation awareness
* Ethical consumer decision-making
* Transparency in fashion supply chains
* Potential integration with regulatory systems (CITES-based monitoring)

The system is designed to be scalable and extensible to additional species.

---

## 🚀 Future Scope

* Integration with blockchain-based supply chain tracking
* Real-time e-commerce product verification
* Expanded dataset for additional species
* Improved explainability using visual heatmaps

---


