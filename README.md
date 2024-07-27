# CALGI: Genotype Data Imputation using KMeans Clustering and Convolutional Autoencoder

## Overview

        CALGI (Clustering and Autoencoder-based Genotype Imputation) is a project designed to fill in missing values in genotype data using KMeans clustering and Convolutional Autoencoder. Simply input a genotype matrix and the original number of clusters (k), and the tool will handle the rest.



## Ensure you have the following packages installed before running the project:
        
        - numpy
        - pandas
        - matplotlib
        - sklearn
        - tensorflow
        - keras
        - pyarrow
        - datatable

## Installation



### 1. Clone the repository
        
        git clone https://github.com/Bingxi-Gao/CALGI.git
                
###  2. Change to the project directory
        
        cd CALGI
                
### 3.  Create a virtual environment
        
        python3 -m venv venv/
                
### 4. Activate the virtual environment
        
        source venv/bin/activate
                
### 5. Install the required dependencies
        
        pip install tensorflow sklearn pandas jupyter matplotlib

## Input Format

## The tool accepts genotype data in the following formats:
        - CSV
        - Feather
        - VCF
        and any other file types that can store genotype information.

## How to Use

        1. Prepare Input Data: Ensure your genotype data is in one of the supported formats (CSV, Feather, VCF, etc.).
        
        2. Run Jupyter Notebook: Open the CALGI.ipynb notebook.
        
        3. Execute Cells: Run the cells in the notebook in sequence to process your data and perform the imputation.

## Project Structure

- CALGI.ipynb: Jupyter Notebook containing the code for data preprocessing, clustering, and autoencoder model training and imputation.

## Detailed Steps

        1. Data Preprocessing: Load and preprocess the input genotype data to the correct format required for imputation.
        2. Clustering: Apply KMeans clustering to group the data into k clusters.
        3. Autoencoder Training: Train a Convolutional Autoencoder on the clustered data.
        4. Imputation: Use the trained autoencoder to fill in missing values in the genotype data.

## License

        This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

        This project utilizes several open-source libraries, including TensorFlow, Keras, and Scikit-learn. We appreciate the contributions of the open-source community.

---

Feel free to reach out for any questions or further assistance. Happy coding!
