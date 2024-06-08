# **Plant Disease Classification**

The goal of this project is to develop an automated system that can identify and classify plant diseases from images of plant leaves. This is crucial for agricultural technology as early detection of diseases can lead to timely intervention, reducing both the spread of disease and economic losses. This project will help in understanding the practical application of CNNs in a real-world problem and exploring various architectures.

**Data Collection/Preparation**

In this section, I gather and prepare the dataset necessary for training the models. The data involves images of plant leaves from various classes, each representing a different plant disease. The dataset is augmented to enhance model generalizability, involving transformations like rotation, zoom, and flips. This preparation ensures the models are trained on a robust dataset that simulates a variety of real-world conditions.

**Modelling**

The modelling section details the construction and training of convolutional neural networks (CNNs) designed to classify images of plant diseases. I use TensorFlow/Keras to build two separate models with different architectures to compare their performance. Each model includes layers for convolution, activation, pooling, and dense connections, tailored to extract features and perform classification tasks effectively.

**Validation and Interpretation**

Evaluation is conducted by applying the trained models to a separate test dataset that the models have not seen during training. I use metrics such as accuracy, precision, recall, and F1-score to assess the performance of the model. This section includes the setup for these metrics and discusses the results obtained from the models. This section also interprets the outcomes of the models' performance. It includes a discussion on how different architectural choices and training parameters impacted the results. 


## **Data Setup Instructions**

To ensure seamless operation of the Jupyter Notebook in Google Colab, please follow these steps to set up the data and model files in your Google Drive:

- Access Data and Model Files:

Use the provided shareable links to access the folders and files necessary for this project. You will find the links down below.

- Add to Your Google Drive:

For each shareable link, open the link and then choose "Add shortcut to My Drive" or "Make a copy" to add the data and model files to your own Google Drive. This step is crucial for ensuring the paths in the Jupyter Notebook correspond to the actual data locations in your Google Drive.

- Folder Structure:

Ensure that the structure of the folders and files in your Google Drive matches the paths specified in the Notebook. It should contain: The full dataset folder, the test dataset folder, two .h5 files for the models and a file with labels for the dataset.

Shareable links:  
Full dataset: https://drive.google.com/drive/folders/1OPwxKLVlBIfxR5xRvo74f642IWjIzQPe?usp=sharing  
Test dataset: https://drive.google.com/drive/folders/17E9TQKf6OE4Yj8LAlV7l9bef8bjexDvt?usp=sharing  
Model 1: https://drive.google.com/file/d/1-CADCXfdSe_f9dHxH5FL9sa5Rh-cTYSj/view?usp=sharing  
Model 2: https://drive.google.com/file/d/1-p1w6HxROH7Pp6f7g9o1Hoqgp6FikCzg/view?usp=sharing  
Label file: https://drive.google.com/file/d/17IeO1jrjj2z6BJU3zH_rCF9EsCrrC24e/view?usp=sharing  

Link of Notebook on Colab if the the access on GitHub doesn't work:  
https://colab.research.google.com/drive/1z9j9pOXbhj4Q1RImJfLhXYLV1eJ3X0op?usp=sharing


- Verify Paths:

Before running the notebook, verify that the paths to the datasets and models in the notebook match those in your Google Drive. Adjust any paths if necessary to reflect where you have stored the files within your Drive.

## **Running the Notebook**

Before you start running the Jupyter Notebook, please note the following:

- Installing Dependencies:
To ensure the smooth running of the Jupyter Notebook, you may need to install certain dependencies. These dependencies include libraries and packages used throughout the notebook for data manipulation, modeling, and visualization. If you encounter any errors related to missing packages, you can install them using !pip install <package_name> directly within your Google Colab notebook.

- Pre-computed Results:
All cells in the notebook have been executed, and the outcomes are visible. This includes results from data processing, modeling, and evaluations.

- Model Training Time:
The modeling section involves training deep learning models, which can be time-consuming. Given that the results of these training sessions are already visible and saved in the notebook, you may choose to skip re-running these sections to save time.

- Test Dataset:
There is no need to create a separate test folder for the test dataset. I have provided a shareable link to the pre-prepared test dataset folder. You can directly use this to evaluate the models without re-creating or re-downloading the test data. You can also skip re-running this cell.

