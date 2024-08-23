# Diet Recommender and Object Detection Project

This project is a combination of a diet recommender system and an object detection model. The project is divided into two main parts: the Diet Recommender and the Object Detection model.

## Project Structure

### **Classifying_food-1/**
- **CSV/**
  - `Dataset.csv`: Contains the dataset used for the diet recommender.
  - `RAW_recipes.csv`: Raw recipes data used for preprocessing.

### **DietRecommander/**
- **etc/**: Configuration files or miscellaneous scripts.
- **Lib/**: Libraries and custom modules used in the project.
- **Scripts/**: Scripts used for preprocessing, training, or other tasks.
- **share/**: Shared resources such as documentation, images, or auxiliary files.

### **Object-Detection-1/**
- **test/**
  - **images/**: Images used for testing the object detection model.
  - **labels/**: Labels corresponding to the test images.
- **train/**: Training data for the object detection model.
- **valid/**: Validation data for the object detection model.
- `data.yaml`: Configuration file for the object detection model.
- `README.dataset.txt`: Documentation for the dataset used in object detection.
- `README.roboflow.txt`: Instructions or documentation related to Roboflow integration.

### **Miscellaneous Files**
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `pyvenv.cfg`: Python virtual environment configuration file.
- `foodRecommandationModel.sav`: The saved model for the diet recommender.
- `requirements.txt`: Lists all Python dependencies required to run this project.
- `test.ipynb`: Jupyter notebook for testing.
- `test2.ipynb`: Another Jupyter notebook for testing.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/farout101/diet_recommandation.git
   cd diet_recommandation
