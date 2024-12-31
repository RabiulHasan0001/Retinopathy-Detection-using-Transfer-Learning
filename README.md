# How to Use This Repository

This repository contains all the code and data required for the project, organized by tasks as outlined in the project instructions. Below is a guide for using the contents of the repository effectively.

## Repository Structure

The repository is organized into folders corresponding to different tasks:

- `TASK-A`: Contains notebooks and scripts for fine-tuning pretrained models on the DeepDRiD dataset.
- `TASK-B`: Includes a notebook for conducting training using additional datasets. Modify augmentation and sampling methods to generate the required data.
- `TASK-C`: Implements attention mechanisms like self-attention, channel attention, and spatial attention.
- `TASK-D`: Features separate notebooks for bagging, boosting, and weighted average ensemble methods. Data preprocessing techniques and ensemble learning approaches are provided here.
- `TASK-E`: Provides tools for creating visualizations and implementing Explainable AI techniques such as GradCAM.

## Task-Specific Instructions

### TASK-B: Two-Stage Training with Additional Datasets

1. Navigate to the `TASK-B` folder.
2. Open the provided notebook.
3. To generate the required data:
   - Change the augmentation method by modifying the respective section in the notebook.
   - Update the sampling method based on your requirements.
   - Use the provided datasets (e.g., Kaggle DR Resized or APTOS 2019 Blindness Detection).
4. Run the notebook to train the model using your chosen configurations.

### TASK-D: Ensemble Learning and Image Preprocessing

1. Navigate to the `TASK-D` folder.
2. Separate notebooks are provided for different ensemble techniques:
   - **Bagging**: Evaluate this method using default augmentation and compare results with unsampled and sampled data.
   - **Boosting**: Train models using boosting techniques as described in the corresponding notebook.
   - **Weighted Average**: Combine model predictions using weighted average and evaluate performance.
3. Experiment with different preprocessing methods (e.g., Ben Graham transformation, CLAHE, circle cropping) to assess their impact on model performance.
4. Analyze results by comparing evaluation metrics such as Cohen Kappa scores.

## Notes

- Ensure that the required datasets are downloaded and placed in the appropriate directories as specified in each notebook.
- All trained models are saved in the respective task folders for easy reference.
- Modify hyperparameters, augmentations, and training strategies as needed to improve results.
- Use visualizations and GradCAM results from `TASK-E` to interpret model predictions and improve understanding of model behavior.

---

