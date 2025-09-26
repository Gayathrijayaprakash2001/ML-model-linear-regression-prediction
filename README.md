# ML-model-linear-regression-prediction...
🧪 Molecular Solubility Prediction Using Linear Regression
📝 Project Overview

This project implements a Linear Regression model to predict the aqueous solubility (logS) of molecules based on their chemical descriptors. Accurate solubility prediction is important in drug discovery, chemical research, and material design.

🎯 Aim

To develop a predictive model that estimates molecular solubility from descriptors like MolLogP, MolWt, NumRotatableBonds, and AromaticProportion.

🔨 Work Done

1) Loaded and analyzed a molecular dataset containing chemical descriptors and solubility values.

2) Implemented a Linear Regression model using scikit-learn.

3) Split the dataset into training and testing sets for model evaluation.

4) Predicted solubility (logS) and compared predictions against actual values.

5) Evaluated model performance using Mean Squared Error (MSE) and R² Score.

6) Visualized predictions vs actual solubility values using scatter plots and regression lines.

📌 Expected Output

A regression model that predicts logS values for molecules.

Visualizations showing how predicted solubility matches experimental data.

Quantitative metrics (MSE, R²) to assess model accuracy.

✅ Achieved Output

Trained Linear Regression model with good predictive performance.

Training R²: ~0.76, Test R²: ~0.79, indicating strong correlation.

Generated regression plots showing predicted vs experimental solubility.

Demonstrated that molecular descriptors can effectively estimate solubility.

🛠️ Technologies Used

Python 3.x

Jupyter Notebook

Pandas & NumPy → Data manipulation and preprocessing

Matplotlib → Data visualization

Scikit-learn → Linear Regression model and evaluation metrics
