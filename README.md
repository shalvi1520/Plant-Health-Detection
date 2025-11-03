A Hybrid CNN–Fuzzy Logic Model for Predictive Health Assessment of Rare and Ornamental Plants in Botanical Gardens  

This project presents a hybrid deep learning system that combines a Convolutional Neural Network (CNN) with a Fuzzy Logic Inference System (FIS) for predictive plant health monitoring.
While CNNs have achieved strong performance in agricultural disease detection, this project extends their application to rare and ornamental plants commonly found in botanical gardens, focusing on interpretability and data scarcity handling.
Plant disease detection is a critical task for biodiversity conservation and smart garden management.
This system performs:
1.Feature extraction & classification using a CNN (MobileNetV2/Custom CNN).
2.Health interpretation using a Fuzzy Logic layer to categorize outputs into Healthy, Moderately Unhealthy, or Diseased.
3.The hybrid CNN–Fuzzy framework provides explainable decision-making with confidence scores that mimic expert horticulturist assessments.
Features:
1.Real-time plant disease classification from leaf images
2.CNN for deep visual feature extraction
3.Fuzzy logic for explainable, human-like health grading
3.Data augmentation for improved generalization
4.Model saving and visualization of training accuracy/loss
5.Easy deployment on Colab, Jupyter, or local Python setup

Dataset:
The project uses the PlantVillage Dataset publicly available on Kaggle:
🔗 PlantVillage Dataset – Kaggle
