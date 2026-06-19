# Uncertainty aware AI-based model to estimate wind demand based on observed damage to single-family residential housing

This project proposes determining the demand experienced by single-family houses after hurricanes by combining visual information from housing facades with deep learning tools. This prediction model is possible because the construction industry develops similar designs for single-family housing. We used the Saffir-Simpson Hurricane, wind scale due to its mapping from descriptors to damage and wind levels. 

This was part of the NHERI GSC 2025 AI Challenge on May 2025. We used the model ViTForImageClassification. We selected the "Wind Track for single family housing". https://www.designsafe-ci.org/data/browser/public/designsafe.storage.published/PRJ-4186

In this project, we developed an AI-driven framework using deep-learning image classifiers and a Bayesian fusion algorithm to generate probabilistic wind-demand estimates with quantified uncertainty. By building classification tools for determining the damage severity of housing, wall damage and roof damage, it delivers confidence bounds for risk-informed decisions. Future work will integrate adaptive fusion strategies, and a broader range of building types to strengthen residential resilience against extreme wind events.

Contributions:
Lissette Iturburu: Conceptuabilization of the framework, coding,  hyperparameter tunning, data labelling; Xiaoyu Liu: Conceptuabilization of the framework, hyperparameter tunning, data labelling. Naomi Rahman: hyperparameter tunning, data labelling: Tabitha Gibbs: conceptualizaiton. 

Cite:
Iturburu, L., Liu, X., Rahman, N., & Gibbs, T. (Year). Uncertainty aware AI-based model to estimate wind demand based on observed damage to single-family residential housing. DesignSafe-CI. https://doi.org/10.17603/ds2-ys8y-1n91
To train the neural networks, we used the data available here: https://github.com/alenjani/hurricane_damage_detection.

<img width="2784" height="1568" alt="image" src="https://github.com/user-attachments/assets/705b5ed1-dc06-4b9d-8275-40a6e5845754" />
