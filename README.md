# Sector Model Accuracy Assessor

This is a browser-based regression analytics tool for assessing model fit on a single uploaded sector dataset.

## Features

- Upload CSV
- Choose target variable
- Choose predictor variables
- Run OLS regression
- Compute:
  - RSS
  - TSS
  - R²
  - Adjusted R²
  - RSE
  - RMSE
- Show visual analytics:
  - Actual vs Predicted
  - Residuals vs Predicted
  - Residual Histogram
  - Feature Magnitude View
  - 3D Multidimensional Plot
- Simulate cross-sector transfer accuracy under:
  - feature mean shift
  - feature scale shift
  - noise inflation

## Interpretation

- Smaller is better:
  - RSS
  - RSE
  - RMSE

- Larger is better:
  - R²
  - Adjusted R²

- TSS is contextual only.
  It is not a model-quality metric by itself.

## Files

- `index.html`
- `README.md`

## Run locally

Open `index.html` in your browser.

## Deploy on GitHub Pages

1. Create a GitHub repository
2. Upload `index.html` and `README.md`
3. Commit to `main`
4. Go to:
   - Settings
   - Pages
5. Select:
   - Source = Deploy from a branch
   - Branch = main
   - Folder = / (root)
6. Save

## Important Note

The cross-sector section is a simulation-based estimate.
It is not real measured accuracy unless you use actual data from another sector.
