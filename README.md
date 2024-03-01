# General Model Training

## Description

General Model Training is a project that provides tools for training a machine learning model to recognize images between two classes using binary crossentropy.

## Features

The project includes the following components:

- **create_dataset.ipynb**: A Jupyter notebook allowing the creation of a customized dataset from an image, generating various variants through rotations, translations, zooms, distortions, etc.

- **model_training_v1.0.0**: A file for training a model using binary crossentropy, enabling the recognition of two classes with values ranging from 0 to 1.

## Usage

To use the `create_dataset.ipynb` notebook, follow these steps:

1. Open the notebook using Jupyter or another compatible environment and follow the instructions for creating the customized dataset.
2. Make sure to have all the necessary libraries installed (`pip install library_name`).

To use the `model_training_v1.0.0` file, follow these steps:

1. Ensure that the data folders are structured correctly in the `data` directory, with images of the desired classes organized into subfolders.
2. Execute the file to initiate the model training process using the provided data in the `data` directory.

## Project Structure

The project is structured as follows:

- **data/**: Contains data folders with images of classes (e.g., dogs, cats).
- **logs/**: Contains log files generated during the model training.
- **create_dataset.ipynb**: The notebook for dataset creation.
- **model_training_v1.0.0**: The file for model training.

## License

This project is released under the [MIT License](LICENSE).
