# Flower Classification using Pytorch
Classification for daisy and dandelion using Neural Network

### Prerequisites

Make sure you have the following installed before running the application:

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


### 1. Installation Using Conda

If you prefer Conda for environment management:

```bash
# Create a conda environment named 'myenv'
conda create --name myenv python=3.10.11

# Activate the conda environment
conda activate myenv

4. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Additional Configuration (*Important*)

 1. `1_numpyarray_vs_tensor.ipynb`: Calculation speed for CPU and GPU example.
 2. `simple_neural_network.ipynb`: Train the pytorch model with custom dataset using Neural Network.
 3. `Load_test_model.ipynb`: Test the trained model `.pt` file with image or directory having images `test.jpg`.
 4. `binary_classification_model.ipynb`: Trained model weight using `simple_neural_network.ipynb` file.
 5. `Flowers_Classification_dataset.zip`: Folders with images for `Train' `Test` `Validation`.
 6. `requirements.txt`: All the required dependencies to execute the `2` and `3`.


