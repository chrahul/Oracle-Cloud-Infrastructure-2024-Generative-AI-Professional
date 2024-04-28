- **Fine-Tuning Configuration Parameters**:
  - **Base Model Selection**: Choose the base model for fine-tuning.
  - **Fine-Tuning Method**: Select either Vanilla or T-Few fine-tuning method.

- **Hyperparameters**:
  - **Total Training Epochs**: Number of iterations through the entire training dataset (default: 3 for T-Few).
  - **Batch Size**: Number of training samples used in one iteration of model training (default: 0.1 for T-Few).
  - **Learning Rate**: Rate at which model parameters are updated after each batch.
  - **Early Stopping Threshold**: Criteria used to decide when the training process should be halted.
  - **Early Stopping Patience**: Parameter used in the process of early stopping to prevent overfitting.
  - **Log Model Matrix Interval in Steps**: Determines how frequently to log model matrix.

- **Evaluation Metrics**:
  - **Accuracy**: Measure of how many predictions the model made correctly out of all predictions.
  - **Loss**: Measure describing how incorrect a prediction is, indicating the quality of predictions.
  
- **Evaluation Process**:
  - **Accuracy Evaluation**: Model predicts certain words in the user uploaded data to assess correctness.
  - **Loss Evaluation**: Model predicts certain words in the user-provided data to evaluate the quality of predictions.
  
- **Evaluation Guidelines**:
  - **Accuracy Check**: Assesses how many predictions the model got right.
  - **Loss Check**: Measures the correctness of incorrect predictions, expecting a decrease in loss as the model improves.
