# Flower Classification using Pytorch

This repository presents a flower classification project that distinguishes between daisy and dandelion flowers using a neural network implemented in PyTorch.

## Notebooks and Files

1. **1_numpyarray_vs_tensor.ipynb**: Explore calculation speed for CPU and GPU with examples.
2. **simple_neural_network.ipynb**: Train the PyTorch model with a custom dataset using a neural network.
3. **Load_test_model.ipynb**: Test the trained model (.pt file) with an image or a directory containing images (test.jpg).
4. **binary_classification_model.ipynb**: Access trained model weights using simple_neural_network.ipynb.

## Dataset and Files

5. **Flowers_Classification_dataset.zip**: Obtain folders with images for Train, Test, and Validation.

## Dependencies

6. **requirements.txt**: View all required dependencies to execute notebooks 2 and 3.


## Prerequisites

Ensure you have the following installed before running the application:

- Python (version 3.10 or higher)
- pip (Python package installer)

## Environment Setup

1. Open a terminal and navigate to the project directory.

### Installation Using pip

2. Create a virtual environment by running the following command:

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```

### Installation Using Conda

If you prefer Conda for environment management:

```bash
# Create a conda environment named 'myenv'
conda create --name myenv python=3.10.11

# Activate the conda environment
conda activate myenv
