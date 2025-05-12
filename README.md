# Water-Quality-Machine-Learning-Model
## Water Quality Model
The Water Quality Prediction Model is a supervised machine learning system designed to classify water samples as either meeting or not meeting defined quality standards. The model was developed using a structured dataset that includes physicochemical and environmental attributes of water samples, such as pH, turbidity, heavy metal concentrations, and temperature.
## Core Methodologies Used:
### Algorithm:

The model utilizes the Random Forest Classifier, a robust ensemble learning method that combines multiple decision trees to improve prediction accuracy and handle feature interactions effectively.

### Feature Selection and Dimensionality Reduction:

Recursive Feature Elimination (RFE): Applied to iteratively remove less significant features, thereby retaining only the most informative attributes.

L1 Regularization (Lasso): Used to impose sparsity by penalizing the absolute values of feature coefficients, promoting automatic feature elimination.

### Sensor Data Integration:

Multi-Sensor Fusion: Combines readings from multiple sensors (e.g., turbidity, conductivity, temperature) to enhance the robustness and completeness of the input data. This fusion strategy helps in capturing complementary aspects of water quality that a single sensor may miss.
## Note
This model was obtained from GitHub and has undergone several modifications.
