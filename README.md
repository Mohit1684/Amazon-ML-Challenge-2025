# Amazon ML Challenge 2025: Smart Product Pricing
**Ranked 298 / 74,000+ (Top 0.4%)** | **Final SMAPE: 47.5357%**

## 📌 Project Overview
Developed a multi-modal machine learning solution to predict e-commerce product prices based on catalog text and product images. The challenge involved handling 75,000 training samples and optimizing for the Symmetric Mean Absolute Percentage Error (SMAPE).

## 🚀 Key Achievements
* **Elite Performance:** Achieved a final SMAPE of **47.5357%**, securing a rank in the top 0.4% of over 74,000 participants.
* **Hybrid Architecture:** Combined traditional NLP (TF-IDF + SVD) with modern embeddings (Vision & Text) using a stacked ensemble of Gradient Boosting models.
* **Robust Feature Engineering:** Extracted Item Pack Quantity (IPQ), volume/weight units, and brand-specific indicators directly from raw text.

## 🛠️ Technical Stack
* **Models:** LightGBM, XGBoost, Ridge Regression (Stacked Ensemble)
* **NLP:** TF-IDF, TruncatedSVD, Text Embeddings (PCA-reduced)
* **Vision:** Pre-trained Image Embeddings (PCA-reduced)
* **Tools:** Scikit-learn, Pandas, NumPy, Scipy

## 📁 Repository Structure
* `47.5357.ipynb`: Main solution notebook containing preprocessing, training, and stacking.
* `methodology.md`: Detailed breakdown of the approach and feature engineering.
* `requirements.txt`: List of dependencies required to run the code.
* `docs/`: Original problem statement and challenge guidelines.

## 🔧 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Place `train.csv`, `test.csv`, and pre-computed embeddings in the directory specified in the notebook configuration.
4. Run the `47.5357.ipynb` notebook.