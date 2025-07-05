# Shapley Values

- used to explain individual model predictions.
- it tells us how each feature has contributed to that prediction.
- It telss us how the model feature has increased or decreased a prediction
- Shap can help answer questions like "how does the model work?" and "how each feature change the prediction?"
- Shap offers additional benefit over feature importance:
    - Individual predictions: SHAP explains why a specific prediction was made by showing each feature's contribution to that prediction — feature importance only shows general global trends.
    - Increased or Decreased Prediction: SHAP indicates whether each feature increased or decreased the model's output (e.g. log-odds or score) for a given instance — feature importance lacks this directionality.
    - Change in Probability of Positive Class (Classification): SHAP can be used to quantify how much each feature shifted the probability of the positive class from the base value — traditional feature importance doesn’t connect features to probability changes.
