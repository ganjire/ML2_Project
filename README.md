Data Collection/Preparation

In this section, I gather and prepare the dataset necessary for training the models. The data involves images of plant leaves from various classes, each representing a different plant disease. The dataset is augmented to enhance model generalizability, involving transformations like rotation, zoom, and flips. This preparation ensures the models are trained on a robust dataset that simulates a variety of real-world conditions.

Modelling

The modelling section details the construction and training of convolutional neural networks (CNNs) designed to classify images of plant diseases. I use TensorFlow/Keras to build two separate models with different architectures to compare their performance. Each model includes layers for convolution, activation, pooling, and dense connections, tailored to extract features and perform classification tasks effectively.

Evaluation

Evaluation is conducted by applying the trained models to a separate test dataset that the models have not seen during training. I use metrics such as accuracy, precision, recall, and F1-score to assess the performance of each model. This section includes the setup for these metrics and discusses the results obtained from the models.

Interpretation

This final section interprets the outcomes of the models' performance. It includes a discussion on how different architectural choices and training parameters impacted the results. I analyze specific cases where the model performed well or poorly to understand the strengths and weaknesses of the approach. Comparisons between the models provide insights into the effectiveness of different neural network configurations for image-based plant disease classification.



----- Data Setup Instructions -----

To ensure seamless operation of the Jupyter Notebook in Google Colab, please follow these steps to set up the data and model files in your Google Drive:

- Access Data and Model Files:

Use the provided shareable links to access the folders and files necessary for this project. You will find links to the full dataset, a separate test dataset folder, and two .h5 model files.

- Add to Your Google Drive:

For each shareable link, open the link and then choose "Add shortcut to My Drive" or "Make a copy" to add the data and model files to your own Google Drive. This step is crucial for ensuring the paths in the Jupyter Notebook correspond to the actual data locations in your Google Drive.

- Folder Structure:

Ensure that the structure of the folders and files in your Google Drive matches the paths specified in the Notebook. The main folder should contain: The full dataset folder, the test dataset folder, two .h5 files for the models and a file with labels for the dataset.

- Verify Paths:


Before running the notebook, verify that the paths to the datasets and models in the notebook match those in your Google Drive. Adjust any paths if necessary to reflect where you have stored the files within your Drive.

----- Running the Notebook -----
Before you start running the Jupyter Notebook, please note the following:

- Pre-computed Results:
All cells in the notebook have been executed, and the outcomes are visible. This includes results from data processing, modeling, and evaluations.

- Model Training Time:
The modeling section involves training deep learning models, which can be time-consuming. Given that the results of these training sessions are already visible and saved in the notebook, you may choose to skip re-running these sections to save time.

- Test Dataset:
There is no need to create a separate test folder for the test dataset. I have provided a shareable link to the pre-prepared test dataset folder. You can directly use this to evaluate the models without re-creating or re-downloading the test data. You can also skip re-running this cell.

