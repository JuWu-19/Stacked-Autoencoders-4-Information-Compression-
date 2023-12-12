### Stacked Denoising Autoencoder for Data Compression

#### Overview
This notebook explains the process of compressing 10,000-dimensional data into 200 dimensions using a Stacked Autoencoder Network with added noise. The data represents four distinct categories.

#### Data Description
The dataset consists of four categories of data, each represented as 10,000-dimensional vectors.

#### Objective
The primary goal is to reduce the dimensionality of the data to 200 dimensions while preserving essential patterns and features, making it suitable for classification tasks. This is achieved through the use of a Stacked Autoencoder Network. The 200-dimensional data obtained from the raw 10,000-dimensional data, after passing through the SAE pipeline, are optimized and ready for subsequent classification processes.

#### Noise Addition
To enhance the robustness of the model, Gaussian noise is added to the original data. This step simulates real-world data imperfections and helps the model learn to denoise and compress effectively.

#### Autoencoder Architecture
The Stacked Autoencoder Network is designed comprised of multiple layers with sufficient representation capacities to gradually compress the data from 10,000 dimensions to 200 dimensions. The architecture includes encoding layers for compression and decoding layers for reconstruction.

#### Training Process
The model is trained on the noisy data, with the original data serving as the target for reconstruction. This process allows the network to learn how to compress and denoise the data simultaneously.

#### Evaluation
The performance of the model is evaluated based on its ability to denoise, compress and reconstruct the data with minimal loss of information.

#### Results
After training, the model successfully compresses the 10,000-dimensional data into 200 dimensions for each of the four categories, demonstrating effective dimensionality reduction and noise removal. The compressed data are well-suited for further analysis, including classification tasks.

#### Usage Instructions
Detailed instructions on how to use the provided code to compress new datasets are included in the notebook. This includes steps for data preparation, model training, and inference.

#### Dependencies
A list of required libraries and dependencies for running the code is provided in the notebook.
