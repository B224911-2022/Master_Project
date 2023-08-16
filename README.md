***Prediction of protein-ligand interactions via modern machine learning methods to accelerate medicine discovery***
The related scripts, models and environment for dissertation project of B224911

In this study, TocoDecoy (a decoy generation method) is utilized as an alternative to DeepCoy to further reduce dataset bias 
and retrain the XGBoost model in SCORCH in an attempt to improve performance.

The results showed that the decoys created by the new TocoDecoy did not enhance the original SCORCH model due to limited chemical diversity.
Furthermore, models retrained using the combined TocoDecoy and DeepCoy decoys with tuned hyperparameters show improved performance compared to SCORCH. 
However, all models exhibit insufficient generalization ability on independent benchmark datasets. The findings highlight the critical importance of the chemical diversity and breadth of the bait dataset for MLSF performance.
Furthermore, TocoDecoy alone is not suitable for model training, but its combination with various decoy sources reveals the potential for model improvement. 
At the same time, the hyperparameter optimization step in the training model will also affect the performance, which needs to be paid attention in the follow-up research.

Although this study did not significantly improve the performance of SCORCH's XGBoost model, 
it provided valuable insights into factors influencing MLSF construction. Continuous optimization of 
data representation and training procedures will further enhance MLSF, advance structure-based virtual screening, and accelerate drug discovery.
