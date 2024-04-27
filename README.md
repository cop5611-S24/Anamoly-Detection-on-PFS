# Anamoly-Detection-on-PFS

SentiLog introduces a novel approach in high-performance computing, specifically targeting parallel file systems (PFSes). It employs deep learning techniques to scrutinize the emotional undertones of developers' logging statements, with the goal of enhancing anomaly detection efficiency. By tackling key challenges in PFS log analysis, SentiLog emerges as an innovative and robust solution in the ever-evolving landscape of high-performance computing. In our project, we successfully integrated the BiLSTM model as described in the referenced paper. Moreover, we implemented another model utilizing Transformers, which demonstrated slightly better performance. These implementations were achieved using the TensorFlow Keras framework.

## Getting Started

### Prerequisites
Below are the required software/libraries that need to be installed
1. IDE: Visual Studio Code. You can use any other editors such as PyCharm/Spyder
2. Python
3. Keras Tensorflow
4. Numpy
5. sklearn
6. matplotlib
7. sklearn seaborn

### How to run
1. Download the AOS_Project folder to your local machine
2. AOS-Project/filter contains the preprocessed data. You need to replace the file path accordingly.
3. **os-project.ipynb** demonstrates the BiLSTM model using the Tensorflow Keras framework.
5. os-transformer-model.ipynb demonstrates the Transformer model using the Tensorflow Keras framework.
6. Run each file separately to know the model definition, training and testing. 


## Team Members
1. Avaneeshakrishna Shastry Chakracodi
2. Akhil Gorthi Bala Sai
3. Sohail Uddin Syed
 

## SentiLog: Anomaly Detecting on Parallel File Systems via Log-based Sentiment Analysis

* **Di Zhang, Dong Dai and Runzhou Han, Mai Zheng** - *Initial work* - [Link to paper](https://dl.acm.org/doi/10.1145/3465332.3470873)

