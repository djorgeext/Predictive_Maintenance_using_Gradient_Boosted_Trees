# Predictive_Maintenance_using_Gradient_Boosted_Trees
This project uses a machine learning model to predict when a machine might fail. It's a simple way to understand and use predictive maintenance.

## About The Project

The goal of this script is to predict machine failure based on sensor data. We use a dataset called "AI4I 2020 Predictive Maintenance Dataset".

The script does the following:

  - Loads the data.
  - Selects the important features for prediction.
  - Splits the data into a training set and a testing set.
  - Trains a Gradient Boosted Trees model.
  - Evaluates how well the model performs.

## Getting Started

Follow these simple steps to get the project running on your computer or in Google Collab.

### Prerequisites

You need to have Python installed. The script uses a few Python libraries that you'll need to install.

  [ydf](https://pypi.org/project/ydf/)
  [pandas](https://pypi.org/project/pandas/)
  [scikit-learn](https://pypi.org/project/scikit-learn/)

### Installation & Usage

1.  Download the Dataset

      You need the "ai4i2020.csv" file. You can find the dataset at the [UCI Machine Learning Repository](https://doi.org/10.24432/C5HS5C).
      Save the file to a location you can easily access.

2.  Install Libraries

    - Open your terminal or command prompt and run this command to install all the necessary libraries:
        ```sh
        pip install ydf pandas sklearn
        ```

3.  Update the Script

      - Open the "predictive_maintenance_using_gradient_boosted_trees.py" file in a text editor.
      - Find this line:
        ```python
        DATASET_PATH = "/content/drive/MyDrive/Challenges_ML-DL/ai4i2020.csv" # change path if necessary
        ```
      - Change the path to where you saved the "ai4i2020.csv" file on your computer.
