# Adversarial-Aware-ML-Pipeline-for-Network-Anomaly-Detection
 Executed end-to-end development of a network anomaly detection model including dataset cleaning, preprocessing, and feature extraction. Engineered a modular ML pipeline integrating classical machine learning and deep-learning approaches. Experimented with GAN-based synthetic traffic generation and Autoencoder.

<img width="335" height="134" alt="image" src="https://github.com/user-attachments/assets/6f3deeed-2656-485b-9c54-7035676e393a" />

[Fig 1 : ROC and Precision–Recall curves comparing AE pretraining (blue) and AE post-adversarial retraining (orange).
]

<img width="320" height="160" alt="image" src="https://github.com/user-attachments/assets/cdca5b47-f0ec-47f5-8798-c1e903948c92" />
[Fig 2 : Confusion matrices (side-by-side) for AE pretrain (left) and AE post-adversarial (right).]

Table 1 — Test set performance 
Model	ROC–AUC	AUPRC	Accuracy	Precision	Recall	F1 Score
AE Pretrain (before adversarial)	0.9288	0.9370	0.8735	0.8760	0.8703	0.8731
AE Post-Adversarial (after retrain)	0.9922	0.9935	0.9716	0.9923	0.9506	0.9710
