# Assumptions and Limitations

## 1. Data Assumptions
- **Stationarity**: Log-returns are assumed stationary; raw prices are not.
- **Event Impact**: Events are assumed to have immediate effects (no lag considered).

## 2. Model Limitations
- **Causality vs Correlation**: Detected change points may correlate with events but do not prove causation.
- **Single-Variable Focus**: Model ignores external factors (e.g., USD strength, inflation).

## 3. Known Biases
- **Event Selection Bias**: Only 10-15 major events are included; minor events ignored.
- **Parameter Sensitivity**: Bayesian priors (e.g., `mu1`, `mu2`) may skew results if misspecified.

## 4. Communication Plan
- **Deliverables**: 
  - Interactive dashboard (Flask + React) for stakeholders.
  - PDF report with methodology and insights.
  