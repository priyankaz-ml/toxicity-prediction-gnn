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


**📈 Visuals**

Per-task ROC-AUC comparison
<img width="1214" height="658" alt="image" src="https://github.com/user-attachments/assets/e4f08479-383b-46cb-8051-dd4106a3d398" />

GNN Training Curve
<img width="1029" height="569" alt="image" src="https://github.com/user-attachments/assets/624805b4-dd82-4ebe-be6b-c5303e85adc0" />

Boxplot of per-task AUCs
<img width="837" height="630" alt="image" src="https://github.com/user-attachments/assets/8429c6d7-e439-40da-acd8-bd1169554474" />

**🔮 Future Work**

Explore other GNNs like GCN, GraphSAGE, GAT for better performance.

Apply hyperparameter tuning and model ensembling.

Add explainability to understand key molecular features.

Expand datasets and try data augmentation for improved generalization.

Build a web app/API for real-time toxicity prediction.

**📝 Author**

Priyanka

