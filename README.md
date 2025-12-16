## Plant-Growth-Predictor-using-PyTorch
This project implements a lightweight neural network to predict plant physical characteristics (phenotypes) based on environmental inputs. Specifically, it uses Linear Regression built on the PyTorch framework to model the relationship between Sunlight, Water, and a plant's final Height.
## Key Features
Excel Integration: Loads raw experimental data directly from Excel/CSV formats using pandas.

Linear Neural Architecture: Utilizes a single-layer nn.Linear module to discover the mathematical weights of growth factors.

Automated Learning: Uses Stochastic Gradient Descent (SGD) to minimize prediction error over 100 training epochs.

Predictive Inference: Includes a dedicated "Evaluation Mode" to predict growth for new, unseen environmental conditions.

## Mathematical Model

The "Brain" of this project learns the following biological equation:

Height = (W_1 × Sunlight) + (W_2 × Water) + Bias

Where W_n represents the sensitivity of the plant species to that specific resource.
