👁️ Eye Disease Classification using Deep Learning (EfficientNet-B0 & ConvNeXt-Tiny)
📌 Overview

This project focuses on automatic classification of retinal fundus images into four categories:

Cataract
Diabetic Retinopathy
Glaucoma
Normal

The system uses deep learning models along with Explainable AI (XAI) techniques to ensure both high accuracy and interpretability, which is crucial for medical applications.

🎯 Objectives
Build a robust image classification model for eye diseases
Compare EfficientNet-B0 and ConvNeXt-Tiny architectures
Achieve high accuracy with good generalization
Apply Explainable AI (Grad-CAM & Score-CAM)
Evaluate performance using multiple metrics
📂 Dataset

👁️ Eye Disease Classification using Deep Learning (EfficientNet-B0 & ConvNeXt-Tiny)
📌 Overview

This project focuses on automatic classification of retinal fundus images into four categories:

Cataract
Diabetic Retinopathy
Glaucoma
Normal

The system uses deep learning models along with Explainable AI (XAI) techniques to ensure both high accuracy and interpretability, which is crucial for medical applications.

🎯 Objectives
Build a robust image classification model for eye diseases
Compare EfficientNet-B0 and ConvNeXt-Tiny architectures
Achieve high accuracy with good generalization
Apply Explainable AI (Grad-CAM & Score-CAM)
Evaluate performance using multiple metrics
📂 Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

Classes:
Cataract
Diabetic Retinopathy
Glaucoma
Normal
⚙️ Model Architecture
🔹 EfficientNet-B0 (Primary Model)
Pretrained on ImageNet
Lightweight and efficient
Custom classification head added
Fine-tuned using transfer learning
🔹 ConvNeXt-Tiny (Comparison Model)
Modern CNN inspired by transformers
Used for performance comparison
🧠 Training Strategy

Training was performed in two phases:

Phase 1 — Head Training
Backbone frozen
Only classifier trained
Faster convergence
Phase 2 — Fine-tuning
Last layers unfrozen
Lower learning rate
Improved generalization
📊 Evaluation Metrics

The model was evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve & AUC
📈 Results
Metric	Value
Test Accuracy	91.18%
Macro F1 Score	0.911
Macro AUC	0.987
🔍 Observations:
Strong performance across all classes
Best performance in Diabetic Retinopathy
Minor confusion between Glaucoma and Normal
🔬 Explainable AI (XAI)

To improve model interpretability, the following techniques were used:

🔹 Grad-CAM
Uses gradients
Provides coarse localization
🔹 Score-CAM
Uses forward activation
Provides sharper and more accurate attention maps
Key Insight:

The model focuses on clinically relevant regions such as:

Optic disc
Retinal vessels
Lesion areas
📊 Visualizations

The project includes:

Training vs Validation curves
Confusion Matrix
ROC Curves
Grad-CAM & Score-CAM visualizations
🚀 Features
End-to-end training pipeline
Model comparison (EfficientNet vs ConvNeXt)
Advanced evaluation metrics
Explainable AI integration
Real-time image upload & prediction
🛠️ Tech Stack
Python
PyTorch
Torchvision
timm
Scikit-learn
Matplotlib & Seaborn
pytorch-grad-cam

Classes:
Cataract
Diabetic Retinopathy
Glaucoma
Normal
⚙️ Model Architecture
🔹 EfficientNet-B0 (Primary Model)
Pretrained on ImageNet
Lightweight and efficient
Custom classification head added
Fine-tuned using transfer learning
🔹 ConvNeXt-Tiny (Comparison Model)
Modern CNN inspired by transformers
Used for performance comparison
🧠 Training Strategy

Training was performed in two phases:

Phase 1 — Head Training
Backbone frozen
Only classifier trained
Faster convergence
Phase 2 — Fine-tuning
Last layers unfrozen
Lower learning rate
Improved generalization
📊 Evaluation Metrics

The model was evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve & AUC
📈 Results
Metric	Value
Test Accuracy	91.18%
Macro F1 Score	0.911
Macro AUC	0.987
🔍 Observations:
Strong performance across all classes
Best performance in Diabetic Retinopathy
Minor confusion between Glaucoma and Normal
🔬 Explainable AI (XAI)

To improve model interpretability, the following techniques were used:

🔹 Grad-CAM
Uses gradients
Provides coarse localization
🔹 Score-CAM
Uses forward activation
Provides sharper and more accurate attention maps
Key Insight:

The model focuses on clinically relevant regions such as:

Optic disc
Retinal vessels
Lesion areas
📊 Visualizations

The project includes:

Training vs Validation curves
Confusion Matrix
ROC Curves
Grad-CAM & Score-CAM visualizations
🚀 Features
End-to-end training pipeline
Model comparison (EfficientNet vs ConvNeXt)
Advanced evaluation metrics
Explainable AI integration
Real-time image upload & prediction
🛠️ Tech Stack
Python
PyTorch
Torchvision
timm
Scikit-learn
Matplotlib & Seaborn
pytorch-grad-cam
