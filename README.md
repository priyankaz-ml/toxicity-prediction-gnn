***🧪 Molecular Toxicity Prediction with Graph Neural Networks (GNNs)***

Predicting molecular toxicity is crucial for drug discovery, chemical safety, and environmental research.
This project explores both classical ML models and Graph Neural Networks (GNNs) on molecular graph data, comparing their performance on toxicity prediction.

**🚀 Features**

Dataset: Tox21 – benchmark dataset for molecular toxicity prediction

**Models Implemented:**

Random Forest – robust baseline

XGBoost – gradient boosting model

Graph Isomorphism Network (GIN) – deep learning model for graph data

Evaluation Metrics: ROC-AUC for classification tasks

**📊 Model Performance**
| Model           | ROC-AUC | Notes                         |
|-----------------|---------|-------------------------------|
| Random Forest   | 0.84    | Best baseline                 |
| XGBoost         | 0.79    | Strong classical model        |
| GIN (GNN)       | 0.819   | Per-task ROC-AUC: 0.70 – 0.87 |


**Key Insights:**

Classical ML (Random Forest) still outperforms deep learning for this dataset.

GNNs are competitive and scale well for graph-structured data.

Visualizations (training curves, boxplots) reveal per-task variability and model stability.

🛠 **Tech Stack**

Python 🐍

PyTorch Geometric (GNNs)

Scikit-learn (Random Forest, XGBoost)

Pandas & NumPy

Matplotlib
