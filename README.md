

# Vanishing Point Detection in Indoor Environments using UNet Segmentaion model

## Introduction
This repository contains the code, models, and dataset for detecting vanishing points in indoor environments. The project aims to accurately identify vanishing points in cluttered scenes, especially those with non-straight lines due to the normalization and resizing of images.

## Models
The project employs two models:
- `model_final.h5`: The final version of the primary model used in the project.
- `model1_final.h5`: The final version of an alternative model.

Additionally, best checkpoint versions of each model are saved as:
- `model_best_checkpoint.h5`
- `model1_best_checkpoint.h5`

## Notebook
- `vpIndv211.ipynb`: This Jupyter Notebook includes all the code related to data preprocessing, model training, and evaluation.

## Dataset
- `toulouse/`: This folder contains the Toulouse dataset used for training and validation of the models.

## Evaluation Metrics
- F1 Scores: `Average F1 Score for model: 0.34` and `Average F1 Score for model1: 0.22`
- Confusion Matrix: Detailed in the `vpIndv211.ipynb` notebook.

## Getting Started



### Instructions

1. **Clone the Repository**:  
   ```
   git clone https://github.com/[Your-Username]/Vanishing-Point-Detection
   ```

2. **Navigate to the Directory**:  
   ```
   cd Vanishing-Point-Detection
   ```

3. **Install Dependencies**:  
   ```
   pip install -r requirements.txt  # You may need to create this file or manually install required libraries
   ```

4. **Run the Notebook**:  
   ```
   jupyter notebook vpIndv211.ipynb
   ```

## Contributors
- [Prateek Pal],[Mohamed Elawady](https://github.com/[walter789])

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.  

---

